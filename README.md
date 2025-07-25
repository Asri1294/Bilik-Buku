# Bilik-Buku

#  Aplikasi Perpustakaan Buku Digital (CI3 + XAMPP)

Aplikasi ini adalah proyek web berbasis CodeIgniter 3 yang berfungsi sebagai sistem **Perpustakaan Buku Digital**. Dibuat sebagai bagian dari tugas mata kuliah **Pemrograman Web** dengan ketentuan fitur seperti CRUD, session handling, pencarian, dan pagination.

---

##  Fitur 

-  **Create, Read, Update, Delete (CRUD)** data buku
-  **Session login/logout**
-  **Pencarian dan Pagination** data buku
-  Manajemen kategori dan anggota
-  UI responsif (menggunakan AdminLTE)

---

## 🛠️ Teknologi yang Digunakan

- PHP (CodeIgniter 3)
- MySQL
- AdminLTE (UI Template)
- jQuery, Bootstrap, FontAwesome

---

## 📁 Struktur Direktori Penting

| Folder / File         | Deskripsi                                       |
|-----------------------|--------------------------------------------------|
| `application/controllers` | File kontroler (admin, login, dll)         |
| `application/models`      | Model database untuk buku dan user         |
| `application/views`       | Tampilan halaman (akan ditambahkan manual) |
| `assets_style`            | Berisi folder `assets/` dan `image/`       |
| `database/perpus.sql`     | File SQL database yang sudah dimodifikasi  |

---

##  Konfigurasi Web

| Konfigurasi      | Nilai                          |
|------------------|-------------------------------|
| `base_url`       | `http://localhost/perpus-ci3/` |
| `database_name`  | `perpus_ci3`                  |
| `username`       | `root`                        |
| `password`       | *(kosong)*                    |

> 📌 Pastikan konfigurasi ini sesuai di `application/config/config.php` dan `database.php`.

---

##  Akun Login Default

| Role   | Username | Password  |
|--------|----------|-----------|
| Reno   | petugas  |    123    |
| Dinda  | anggota  |    123    |

> Jika tidak bisa login, periksa apakah password menggunakan hash di DB. Bisa diganti manual dengan plain text jika perlu.

---

##  Screenshot Tampilan

> Sertakan screenshot UI berikut dalam laporan:
- Halaman Login
- Dashboard
- Daftar Buku
- Form Tambah/Edit Buku
- Halaman Pencarian

---

## 📦 Cara Menjalankan Proyek

1. **Salin folder ke `htdocs/`**
2. **Import file `project_perpus.sql` ke phpMyAdmin**
3. **Edit konfigurasi database di `application/config/database.php`**
4. **Buka `http://localhost/perpus-ci3/` di browser**

---

##  Laporan Singkat

Berisi:
- Tujuan pembuatan web
- Penjelasan tiap fitur
- Struktur folder penting
- Proses instalasi
- Screenshot UI
- Link YouTube

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

## 📝 Lisensi

Proyek ini digunakan hanya untuk **tujuan edukasi** dan tugas kuliah. Semua hak cipta dan properti UI tetap milik pembuat aslinya. Silakan gunakan dan modifikasi dengan bijak.

