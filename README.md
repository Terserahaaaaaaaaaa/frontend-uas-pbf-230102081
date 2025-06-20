**Langkah-langkah membuat frontend Laravel untuk studi kasus Rumah Sakit**

---

````markdown
# 🏥 Backend Rumah Sakit - Laravel

Repositori ini berisi proyek front end menggunakan **Laravel** untuk sistem informasi rumah sakit dengan dua entitas utama: `pasien` dan `obat`.

---

## 📌 Studi Kasus

Sistem ini dirancang sebagai **antarmuka (frontend)** untuk menampilkan dan mengelola data **obat** pada sistem informasi rumah sakit.

Halaman ini mempermudah pengguna (admin atau petugas farmasi) dalam:
- Melihat daftar obat yang tersedia
- Menambahkan data obat baru
- Mengedit atau menghapus data obat

---

## ⚙️ LANGKAH-LANGKAH PEMBUATAN FRONTEND

### 1. Persiapan Awal

Pastikan perangkat Anda telah terinstall:
- PHP >= 8.1
- Composer
- MySQL/MariaDB
- Git

### 2. Buat Proyek Laravel Baru
    buat project laravel baru
```bash
composer create-project laravel/laravel backend_rumahsakit
cd backend_rumahsakit
````
## 🗂️ Struktur Folder Utama

frontend-uas-230302080/
├── public/
│   └── index.php
├── resources/views/
│   ├── layouts/
│   │   └── app.blade.php
│   ├── obat/
│   │   ├── index.blade.php     # Daftar obat
│   │   ├── create.blade.php    # Tambah obat
│   │   └── edit.blade.php      # Edit obat
│   └── pasien/
│       ├── index.blade.php     # Daftar pasien
│       ├── create.blade.php    # Tambah pasien
│       └── edit.blade.php      # Edit pasien
└── README.md
