# UTS_PemrogramanVisual

# 🍰 Brownie House Management System

Brownie House Management System adalah aplikasi berbasis web yang dirancang untuk mengelola data operasional toko kue Brownie House. Sistem ini menyediakan fitur pengaturan sistem, manajemen pengguna, menu aplikasi, serta berbagai utilitas pendukung agar operasional dapat berjalan dengan efisien.

---

## 🖥️ Tampilan dan Alur Aplikasi

### 1. Halaman Login
Halaman awal yang digunakan pengguna untuk masuk ke sistem.  
Terdapat input username, password, opsi “Stay signed in”, serta tombol **Sign In**.  
Pengguna yang berhasil login akan diarahkan ke halaman utama (Dashboard).

---

### 2. Dashboard
Setelah login, pengguna akan melihat halaman utama dengan tampilan logo dan gambar interior toko Brownie House.  
Terdapat kalimat sambutan yang menekankan kemudahan dan kenyamanan pelanggan.  
Di sisi kiri terdapat **sidebar menu** untuk mengakses berbagai fitur utama seperti Sistem Manager, Master Data, dan Administration Tools.

---

### 3. Sistem Manager
Menu ini berfungsi sebagai pusat pengaturan utama sistem.  
Admin dapat mengelola pengguna, peran, serta hak akses masing-masing role.  
Fitur di dalamnya mencakup:
- **Setup** → mengatur user, role, dan role option.  
- **Utility** → upload laporan, cek status server, serta mengelola dokumen sistem.

---

### 4. User Management
Berisi tabel daftar pengguna yang terdaftar di sistem, menampilkan kolom seperti ID User, Role, Status, dan Waktu Login terakhir.  
Admin dapat menambahkan user baru, mengedit data, atau menghapus pengguna lama.  
Contoh: user `adminit` dengan role `IT DEV` aktif, serta user `stafit` sebagai staf pengembang.

---

### 5. Administration Tools
Berfungsi untuk mengatur konfigurasi aplikasi dan struktur menu yang muncul di sidebar.  
Admin dapat menyesuaikan tampilan aplikasi, mengatur pesan standar, serta melakukan pengelolaan database.  
Submenu penting:
- **Configuration** → pengaturan tampilan dan sistem dasar.  
- **Standard Messages** → teks notifikasi dan alert standar.  
- **App Management** → meliputi Menu Management, User Identity, Database Utility, dan Utilities tambahan.

---

### 6. Menu Management
Tempat untuk membuat dan mengatur struktur menu di dalam sistem.  
Admin dapat menambahkan menu baru dengan menentukan ID, nama menu, parent menu, urutan tampil, ikon, dan status aktif.  
Contoh menu:
- Sistem Manager (`fa fa-cogs`)
- Master Data (`fa fa-database`)
- brownies (`fa fa-coffee`)
- Developer Area (`fa fa-user`)

---

### 7. Menu Editor
Digunakan untuk menambah atau mengubah menu yang sudah ada.  
Formulirnya berisi kolom seperti Menu ID, Name, Parent, Level, Sequence, Link, Icon, Tag1, Tag2, dan Status.  
Tombol **SAVE** untuk menyimpan perubahan dan **BACK** untuk kembali ke daftar menu.

---

## 🔄 Alur Sistem Secara Umum
1. Pengguna membuka halaman login dan masuk menggunakan akun terdaftar.  
2. Setelah berhasil login, sistem menampilkan Dashboard utama.  
3. Dari Dashboard, admin dapat membuka Sistem Manager untuk mengatur user dan role.  
4. Setelah pengaturan role selesai, admin dapat menyesuaikan menu yang muncul melalui Menu Management.  
5. Semua pengaturan disimpan otomatis dan dapat diakses kembali melalui Administration Tools.

---

## 🧱 Struktur Menu Sidebar
