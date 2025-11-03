# UTS_PemrogramanVisual
## PROFIL
| Variable           |             Isi            |
| -------------------|----------------------------|
| **Nama**           |         Oktavia Rizkha Kurniawati       |
| **NIM**            |          312310509         |
| **Kelas**          |          TI.23.A.5         |
| **Mata Kuliah**    |     Pemograman Visual (Desktop)     |
| **Dosen Pengampu** | Dr. Muhamad Fatchan, S.Kom., M.Kom. |

# 🍰 Brownie House Management System

Brownie House Management System adalah aplikasi berbasis web yang dirancang untuk mengelola data operasional toko kue Brownie House. Sistem ini menyediakan fitur pengaturan sistem, manajemen pengguna, menu aplikasi, serta berbagai utilitas pendukung agar operasional dapat berjalan dengan efisien.

---

## 🖥️ Tampilan dan Alur Aplikasi

### 1. Halaman Login

<img width="983" height="506" alt="image" src="https://github.com/user-attachments/assets/f8d40e64-327d-48a8-bc5e-a95cc7ecde10" />

Halaman awal yang digunakan pengguna untuk masuk ke sistem.  
Terdapat input username, password, opsi “Stay signed in”, serta tombol **Sign In**.  
Pengguna yang berhasil login akan diarahkan ke halaman utama (Dashboard).

---

### 2. Dashboard

<img width="979" height="472" alt="image" src="https://github.com/user-attachments/assets/9f8c9639-bd37-4be3-893d-b6f18409ee01" />

Setelah login, pengguna akan melihat halaman utama dengan tampilan logo dan gambar interior toko Brownie House.  
Terdapat kalimat sambutan yang menekankan kemudahan dan kenyamanan pelanggan.  
Di sisi kiri terdapat **sidebar menu** untuk mengakses berbagai fitur utama seperti Sistem Manager, Master Data, dan Administration Tools.

---

### 3. Sistem Manager

<img width="839" height="486" alt="image" src="https://github.com/user-attachments/assets/392abfa0-f4aa-4417-8b67-fff919175906" />

Menu ini berfungsi sebagai pusat pengaturan utama sistem.  
Admin dapat mengelola pengguna, peran, serta hak akses masing-masing role.  
Fitur di dalamnya mencakup:
- **Setup** → mengatur user, role, dan role option.  
- **Utility** → upload laporan, cek status server, serta mengelola dokumen sistem.

---

### 4. User Management

<img width="989" height="439" alt="image" src="https://github.com/user-attachments/assets/af046ec7-d328-4e6b-b6ba-adbabe178578" />

Berisi tabel daftar pengguna yang terdaftar di sistem, menampilkan kolom seperti ID User, Role, Status, dan Waktu Login terakhir.  
Admin dapat menambahkan user baru, mengedit data, atau menghapus pengguna lama.  
Contoh: user `adminit` dengan role `IT DEV` aktif, serta user `stafit` sebagai staf pengembang.

---

### 5. Administration Tools

<img width="1064" height="404" alt="image" src="https://github.com/user-attachments/assets/db0c7a64-b815-4997-991f-310ffdff0e10" />

Berfungsi untuk mengatur konfigurasi aplikasi dan struktur menu yang muncul di sidebar.  
Admin dapat menyesuaikan tampilan aplikasi, mengatur pesan standar, serta melakukan pengelolaan database.  
Submenu penting:
- **Configuration** → pengaturan tampilan dan sistem dasar.  
- **Standard Messages** → teks notifikasi dan alert standar.  
- **App Management** → meliputi Menu Management, User Identity, Database Utility, dan Utilities tambahan.


---

### 6. Menu Editor

<img width="1023" height="456" alt="image" src="https://github.com/user-attachments/assets/101c19e8-99e2-4d73-9c58-b2e649e62a43" />

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

## 🧰 8. Teknologi & Tools yang Digunakan

- **Desain Prototype:** Balsamiq Mockups  
- **Framework Frontend:** HTML, CSS, dan Bootstrap (opsional)  
- **Backend (jika dikembangkan):** PHP / CodeIgniter  
- **Database (rencana integrasi):** MySQL / MariaDB  
- **Struktur Navigasi:** Sidebar + Topbar + Main Content  

---

## 📦 9. Kesimpulan

Tampilan website **Brownies Management System** dirancang dengan struktur antarmuka yang konsisten, memudahkan pengguna untuk mengelola data dengan cepat dan efisien.  
Setiap halaman memiliki fungsi spesifik yang saling terhubung, mulai dari **login**, **navigasi**, **pengelolaan data**, hingga **pengaturan tampilan**.

---
| No | Judul Video | Platform | Link YouTube |
|----|-------------|---------|-------------|
| 1  | UTS Pemrograman Visual: Website Brownies Management System dengan MongoDB & IIS | Desktop | [Tonton di YouTube](https://youtu.be/2gIi-d1YR68?si=kmkjEKPhnVGpLRFw) |





🧡 *Dokumentasi ini dibuat untuk menjelaskan tampilan dan alur kerja aplikasi secara visual dari proses awal hingga akhir.*
