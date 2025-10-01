1. Mengapa pengecekan pada struktur IF tersebut tidak melibatkan kondisi dengan 
operator relasional? 
Jawab: Karena variabel uktLunas sudah bertipe boolean (hanya bernilai true atau false). Jadi tidak perlu membandingkan lagi dengan operator relasional (misalnya == true). Cukup menggunakan if (uktLunas).

2. Saat program dijalankan, kemudian Anda mengisikan nilai false, bagaimana hasilnya? 
Jawab: Program tidak akan menampilkan KRS, karena kondisi IF tidak terpenuhi. Jadi output program kosong (tidak ada pesan tambahan).

3. Sistem perlu memberikan informasi apabila pengguna memasukkan nilai false, maka 
terdapat keluaran “Registrasi ditolak. Silakan lunasi UKT terlebih dahulu”. Modifikasi 
program tersebut dengan menambahkan struktur ELSE! 
Jawab: Dengan menambahkan else, jika nilai uktLunas == false, maka sistem menampilkan pesan tersebut.

4. Commit dan push hasil modifikasi Anda ke Github dengan pesan “Modifikasi 
Percobaan 1” 
Jawab:
 git add ifCetakKRS07.java
 git commit -m "Modifikasi Percobaan 1"
 git push origin main