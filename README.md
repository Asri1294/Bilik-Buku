# Bilik-Buku

#  Aplikasi Perpustakaan Buku Digital (CI3 + XAMPP)

Aplikasi ini adalah proyek web berbasis CodeIgniter 3 yang berfungsi sebagai sistem **Perpustakaan Buku Digital**. Dibuat sebagai bagian dari tugas mata kuliah **Pemrograman Web II** dengan ketentuan fitur seperti CRUD, session handling, searching, dan pagination.

---

##  Fitur 

-  **Create, Read, Update, Delete (CRUD)** 
-  **Session login/logout**
-  **Pencarian dan Pagination** data buku
-  **Manajemen kategori dan anggota**
-  **UI responsif** 

---

##  Teknologi yang Digunakan

- PHP (CodeIgniter 3)
- Xampp
- jQuery, Bootstrap, FontAwesome

---

##  Struktur Direktori Penting

| Folder / File         | Deskripsi                                       |
|-----------------------|--------------------------------------------------|
| `application/controllers` | File kontroler (admin, login, dll)         |
| `application/models`      | Model database untuk buku dan user         |
| `application/views`       | Tampilan halaman (akan ditambahkan manual) |
| `assets_style`            | Berisi folder `assets/` dan `image/`       |
| `database/projek_perpus.sql`     | File SQL database yang sudah dimodifikasi  |

---

##  Konfigurasi Web

| Konfigurasi      | Nilai                         |
|------------------|-------------------------------|
| `base_url`       | `http://localhost/perpus-ci3/`|
| `database_name`  | `project_perpus`              |
| `username`       | `root`                        |
| `password`       | *(kosong)*                    |

>  Pastikan konfigurasi sesuai di `application/config/config.php` dan `database.php`.

---

##  Akun Login Default

| Role   | Username | Password  |
|--------|----------|-----------|
| Reno   | petugas  |    123    |
| Dinda  | anggota  |    123    |

> Jika tidak bisa login, periksa apakah password menggunakan hash di DB. Bisa diganti manual dengan plain text jika perlu.

---

##  Cara Menjalankan Proyek

1. **Siapkan folder CI3 (ekstrak dari `CodeIgniter-3.1.13.zip`) **
2. **Salin folder CI3 yang sudah diekstrak ke `htdocs/` dan sesuaikan dengan isi folder `perpus-ci3` **
3. **Import file `projek_perpus.sql` ke phpMyAdmin**
4. **Edit konfigurasi database di `application/config/database.php`**
5. **Buka `http://localhost/perpus-ci3/` di browser**

---

##  Laporan Singkat

Berisi:
- Tujuan pembuatan web
- Penjelasan tiap fitur
- Struktur folder 
- Screenshot UI

---

##  Kontributor

- Nama: *[Asria R.]*
- Kelas: *IT402*

---

##  Sumber Referensi

>  Proyek ini dimodifikasi dari repositori [fauzan1892/perpus-ci3] dengan penyesuaian tampilan, nama database, serta penghapusan watermark untuk tujuan edukasi.

- Proyek dasar: [https://github.com/fauzan1892/perpus-ci3](https://github.com/fauzan1892/perpus-ci3)
- Dokumentasi CI3: https://codeigniter.com/user_guide/

---

##  Lisensi

Proyek ini digunakan hanya untuk **tujuan edukasi** dan tugas kuliah. Semua hak cipta dan properti UI tetap milik pembuat aslinya. Silakan gunakan dan modifikasi dengan bijak.

