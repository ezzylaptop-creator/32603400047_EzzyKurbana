PANDUAN BAB 5 CRUD MAHASISWA - EZzy / 32602400047

File yang ditambahkan:
1. app/Models/MahasiswaModel.php
2. app/Controllers/Crud.php
3. app/Views/layout/template.php
4. app/Views/CRUD/View.php
5. app/Views/CRUD/Upload.php
6. app/Views/CRUD/Edit.php
7. public/assets/css/crud.css
8. database/mahasiswa.sql

Langkah menjalankan:
1. Buka XAMPP, aktifkan Apache dan MySQL.
2. Buka phpMyAdmin.
3. Import file database/mahasiswa.sql.
4. Pastikan file .env berisi database.default.database = praktikum.
5. Jalankan di terminal:
   php spark serve
6. Buka browser:
   http://localhost:8080/crud

Route penting:
- /crud    : menampilkan data mahasiswa
- /tambah  : menambah data mahasiswa
- /edit/{nim} : mengedit data mahasiswa
- /hapus/{nim}: menghapus data mahasiswa

Catatan:
Jika nama database kamu bukan praktikum, ubah bagian database.default.database di file .env.
