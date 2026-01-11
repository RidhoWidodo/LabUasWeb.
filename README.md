# LabUasWeb.
- Nama   : Muhammad Ridho Hafiedz
- Nim    : 312410195
- Kelas  : TI.24 A2
- Mata Kuliah : Pemrograman Web
- Dosen  : Agung Nugroho, S.Kom., M.Kom.


***Penjelasan Project. Aplikasi Toko Jual Beli Sparepart Motor.***
*Aplikasi ini dikembangkan menggunakan konsep Object Oriented Programming (OOP) dengan struktur modular dan routing, serta dilengkapi fitur login multi-role, CRUD, pencarian data, pagination, dan desain responsif. Sistem ini dirancang agar dapat digunakan secara langsung oleh bengkel motor skala kecil hingga menengah.*

# Struktur Folder dan File
**Berikut adalah struktur Folder dan File**
```SPARE/
├── admin/
│   ├── kategori/
│   │   ├── edit.php
│   │   ├── hspace.php
│   │   ├── index.php
│   │   └── tambah.php
│   ├── sparepart/
│   │   ├── edit.php
│   │   ├── hspace.php
│   │   ├── index.php
│   │   └── tambah.php
│   ├── users/
│   │   ├── edit.php
│   │   ├── hspace.php
│   │   ├── index.php
│   │   └── tambah.php
│   └── dashboard.php
├── api/
│   ├── add_to_card.php
│   ├── clear_cart.php
│   ├── get_cart_count.php
│   ├── remove_cart.php
│   └── update_cart.php
├── assets/
├── config/
│   ├── constants.php
│   └── database.php
├── include/
│   ├── classes/
│   ├── footer.php
│   ├── functions.php
│   ├── header.php
│   └── tmp/
├── uploads/
│   └── spare/
└── user/
    ├── cart.php
    ├── dashboard.php
    ├── profile.php
    ├── detail_sparepart.php
    ├── index.php
    ├── login.php
    ├── logout.php
    ├── register.php
    ├── sidebar.php
    ├── sparepart.php
    └── tentang.php
```

# Penjelasan Struktur Folder dan File Sistem Manajemen Spare Part
# A. ADMIN SECTION (`admin/`)
Modul untuk administrator sistem yang mengelola konten dan data.

***1. Subfolder Kategori (`admin/kategori/`)***
 - `edit.php` - Form untuk mengedit kategori spare part
 - `hspace.php` - File helper/template (kemungkinan header atau template khusus)
 - `index.php` - Halaman utama manajemen kategori
 - `tambah.php` - Form untuk menambahkan kategori baru

***2. Subfolder Sparepart (`admin/sparepart/`)***
 - `edit.php` - Form edit data spare part
 - `hspace.php` - Template/helper untuk bagian spare part
 - `index.php` - Halaman utama manajemen spare part
 - `tambah.php` - Form penambahan spare part baru

***3. Subfolder Users (`admin/users/`)***
 - `edit.php` - Form edit data pengguna
 - `hspace.php` - Template untuk manajemen user
 - `index.php` - Daftar dan manajemen semua pengguna
 - `tambah.php` - Form penambahan user baru

***4. Dashboard Admin (`dashboard.php`)***
 - `dashboard.php` - Halaman utama admin dengan statistik dan kontrol panel

# B. API ENDPOINTS (`api/`)
API untuk operasi cart/shopping cart secara real-time (AJAX)

***1. Cart Operations:***
 - `add_to_card.php` - Menambahkan item ke keranjang belanja
 - `clear_cart.php` - Mengosongkan seluruh keranjang
 - `get_cart_count.php` - Mendapatkan jumlah item di keranjang
 - `remove_cart.php` - Menghapus item tertentu dari keranjang
 - `update_cart.php` - Memperbarui kuantitas item di keranjang

# C. ASSETS (`assets/`)
 - Folder untuk file statis: CSS, JavaScript, gambar, font, dll.
 - Biasanya berisi: `css/`, `js/`, `images/`, `fonts/`

# D. CONFIGURATION (`config/`)
File konfigurasi sistem

***1. System Configuration:***
 - `constants.php` - Mendefinisikan konstanta global (path, URL, setting)
 - `database.php` - Koneksi database dan setting DB

# E. INCLUDE FILES (`include/`)
File yang di-include di berbagai halaman (reusable components)

***1. Components:***
 - `classes/` - Folder untuk kelas PHP (OOP)
 - `footer.php` - Template footer untuk semua halaman
 - `functions.php` - Fungsi-fungsi helper global
 - `header.php` - Template header untuk semua halaman
 - `tmp/` - Folder temporary untuk file sementara

# F. UPLOADS (`uploads/`)
spare/ - Folder untuk menyimpan gambar/foto spare part yang di-upload

# G. USER SECTION (`user/`)
Modul untuk pengguna biasa/customer

***1. User Features:***
 - `cart.php` - Halaman keranjang belanja user
 - `dashboard.php` - Dashboard pribadi user
 - `profile.php` - Profil dan pengaturan akun user
 - `detail_sparepart.php` - Detail informasi spare part
 - `index.php` - Halaman utama user/landing page

***2. Authentication:***
 - `login.php` - Halaman login
 - `logout.php` - Proses logout
 - `register.php` - Halaman pendaftaran

***3. Navigation & Pages:***
 - `sidebar.php` - Navigasi sidebar untuk user
 - `sparepart.php` - Halaman daftar spare part
 - `tentang.php` - Halaman tentang/tentang kami

***Jadi Kesimpulan: Ini adalah struktur aplikasi web e-commerce/manajemen inventaris spare part dengan sistem multi-user (admin dan customer), dilengkapi dengan shopping cart, manajemen produk, dan sistem autentikasi.***

# Hasil OutPut dan Penjelasannya 
# ***Tampialan Loggin Admnin/User***
<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/88371c9d-655d-441a-ab71-cec7385aab35" />

# ***Tampilan Home***
<img width="959" height="328" alt="image" src="https://github.com/user-attachments/assets/9c058a10-22cb-46e0-a4fe-2dcaee8293ab" />
<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/a815169e-5e15-4b8b-906a-c903805a44c5" />


