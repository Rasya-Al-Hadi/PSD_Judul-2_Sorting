Judul Program : Pengurutan Rekor Lari

Deskripsi :
Program simulasi tentang pengurutan Rekor Lari. User memasukkan Jumlah Pelari, mendata setiap waktu pelari dalam hitungan detik, menyimpan data dalam array, mengurutkan waktu dari yang tercepat sampai terlambat. Program ini menggunakan Insertion Sort yang merupakan salah satu pengurutan algoritma yang sederhana. Elemen ini kemudian dibandingkan dengan elemen sebelumnya (elemen pertama). Jika elemen kedua lebih kecil, maka posisinya ditukar dengan elemen pertama.

Source Code :
<img width="538" height="458" alt="Tugas Akhir PSD 2 (1)" src="https://github.com/user-attachments/assets/4162ca03-f4f3-4dcf-b7fa-a631bab12e44" />
<img width="223" height="58" alt="Tugas Akhir PSD 2 (2)" src="https://github.com/user-attachments/assets/4bc5f32c-d4b0-4080-bc5f-c99fedd53f41" />

Penjelasan :

Baris 1, Mendefinisikan fungsi untuk mengurutkan array (arr) dengan jumlah elemen (n) menggunakan metode insertion sort

Baris 2, Perulangan dimulai dari indeks ke-1 sampai ke (n)

Baris 3, Menyimpan nilai elemen saat ini ke variabel sementara temp

Baris 4, Menentukan indeks sebelumnya (elemen di kiri) untuk dibandingkan

Baris 5, Perulangan untuk membandingkan temp dengan elemen sebelumnya

Baris 6, Menggeser elemen yang lebih besar ke kanan

Baris 7, Pindah ke indeks sebelumnya untuk pengecekan lanjutan

Baris 8, Menempatkan temp pada posisi yang benar setelah pergeseran

Baris 11, Mendefinisikan fungsi utama untuk menjalankan program

Baris 12, "try" digunakan untuk menguji kode dari potensi kesalahan

Baris 13, Meminta input jumlah data (pelari), lalu mengubahnya menjadi integer

Baris 14, digunakan untuk menangkap dan menangani kesalahan tipe data

Baris 15, Jika input bukan angka, tampilkan pesan "Input tidak Valid"

Baris 16, Program dihentikan

Baris 17, Membuat list kosong untuk menyimpan data waktu lari

Baris 18, Menampilkan input kepada User untuk memasukkan waktu lari

Baris 19, Perulangan sebanyak (n) kali untuk memasukkan data

Baris 20, loop tak terbatas untuk memastikan input valid

Baris 21, "try" digunakan untuk menguji kode dari potensi kesalahan

Baris 22, Mengambil input waktu lari dan mengubahnya menjadi integer

Baris 23, Menambahkan nilai ke dalam array

Baris 24, Keluar dari loop jika input valid

Baris 25, digunakan untuk menangkap dan menangani kesalahan tipe data

Baris 26, Jika input bukan angka, tampilkan pesan "Input tidak valid, silakan masukkan angka!" untuk mengulangi input

Baris 27, Menampilkan isi array sebelum dilakukan pengurutan

Baris 28, Memanggil fungsi insertion sort untuk mengurutkan data

Baris 29, Menampilkan pesan ""Data rekor lari setelah diurutkan (tercepat ke terlambat):" dan hasil pengurutan

Baris 30, Perulangan sebanyak (n) kali untuk memasukkan data

Baris 31, Menampilkan setiap elemen array dalam satu baris (hasil sudah terurut)

Baris 32, Membuat baris baru setelah output

Baris 35, Memastikan program dijalankan langsung, bukan diimpor dari file lain

Baris 36, Memanggil fungsi utama agar program berjalan

Output :
<img width="687" height="134" alt="Tugas Akhir PSD 2 (3)" src="https://github.com/user-attachments/assets/34fe85d5-88ad-400b-835d-a63a8f53470a" />

Penjelasan :
User memasukkan Jumlah (n) Pelari, Memasukkan waktu rekor lari dalam hitungan detik dari setiap Pelari, Data rekor disimpan dalam array sebelum diurutkan, Mengurutkan dengan fungsi Insertion Sort dari yang tercepat sampai terlambat 

Link Dokumentasi :
https://youtu.be/AKC04lfRIkQ?si=vEfC67_kKLoxkVr0
