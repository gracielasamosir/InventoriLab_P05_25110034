Praktikum Pertemuan 5 - Database Inventori Laboratorium
Nama  : Graciela Ester Paulina Samosir 
NIM   : 25110034
Kelas : TK-A (25)
Server database : MariaDB/MySQL versi 3.3.0
phpMyAdmin      : versi 127.0.0.1
Nama database   : db_inventori_lab (atau db_inventori_lab_NIM jika nama itu sudah dipakai)

Cara memulihkan database:
1. Jalankan Apache dan MySQL di XAMPP.
2. Buka localhost/phpmyadmin, buat database dengan collation utf8mb4_unicode_ci.
3. Pilih database tersebut > tab Import > pilih skema_inventori_lab.sql > Import.

Isi: 5 tabel (kategori, barang, pengguna, peminjaman, detail_peminjaman), 4 foreign key, 3 check constraint.