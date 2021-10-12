di chapter ini kami mengerjakan project secara tim, anggota daripada tim ini terdiri dari:

1. M Rizki 
2. Deandro Farlinno
3. Biandi
4. Anton

tugas kami di chapter ini adalah :

1. Melanjutkan project yang sudah dibuat pada chapter.
2. Menggunakan design pattern MVC (Model View Controller) pada struktur kode yang besifat monolith.
3. Menggunakan design pattern MCR (Model Controller Router) pada struktur kode yang bersifat JSON (JavaScript Object Notation) REST API.
4. Menggunakan asynchronous pada setipa function
5. Menyesuaikan tabel databse dengan konsep yang diinginkan
6. Membuat tingakatan 2 tingkatan user yaitu:
    - SuperAdmin memiliki hak akses ke semua data yang berada pada database dynamic data authentication pada monolith dashboard.
    - PlayerUser memiliki hak akses terbatas sesuai dengan cakupan pada design game berbentuk JSON digunakan untuk login pada API.
7. PlayerUser menggunakan JWT (JavaScript) authentication untuk login json.
8. Antara player 1 dengan player lainnya bisa bertanding di satu endpoint room dengan menyediakan endpoint pembuatan room dengan input nama kemudian server akan merespon dengan kode sehingga 2 user bisa bermain bersama dengan room kode yang sama.
    - Player akan bermain selama 3 ronde
    - Response server pada hasil permainan berbentuk array sehingga bisa records 3 permainan.
9. Hasil dari setiap pertandingan akan di record ke database user_game_history dan list ditampilkan ke endpooint private yang bisa di akses hanya user.
    - Setelah permainan selesai skor pada game history akan bertambah

Note: point yang tidak dicentang adalah tugas yang kami belum maksimal untuk dikerjakan, karena terdapat beberapa error & stuck yang memakan waktu cukup lama sehingga kami memutuskan untuk mengerjakan tugas lain yang menurut kami bisa diselesaikan.  

Menjalankan project:

Syarat untuk bisa menjalan project ini adalah:

- pastikan di komputer anda sudah terinstall:
    - GIT (minimal versi 2.25.1)
    -

Langkah pertama untuk memulai project sbb:

- 

*buat file .env sejajar dengan file pacckage.json dan isi file tsb dengan*: 
#### SECRET_KEY=mysecret
