# Laragon 6 - Modern & Portable Development Environment

![Laragon Logo](https://laragon.org/assets/img/logo.png)

**Laragon** adalah lingkungan pengembangan (development environment) yang modern, cepat, dan sangat ringan untuk Windows. Laragon 6 hadir untuk memberikan pengalaman pengembangan web yang lebih stabil, portabel, dan terisolasi tanpa mengotori sistem operasi Anda.

## 🚀 Keunggulan Laragon 6

- **Sangat Cepat & Ringan:** Didesain untuk performa maksimal dengan penggunaan RAM yang sangat minim.
- **Portabel:** Anda bisa memindahkan folder Laragon ke folder lain, disk lain, atau bahkan ke USB Flashdrive tanpa merusak konfigurasi.
- **Virtual Hosts Otomatis:** Laragon secara otomatis membuat domain lokal (seperti `proyek-saya.test`) setiap kali Anda membuat folder baru di dalam direktori `www`.
- **Terisolasi:** Tidak menggunakan variabel lingkungan (Environment Variables) sistem secara permanen, sehingga tidak berbenturan dengan software lain.
- **Mudah Digunakan:** Antarmuka yang intuitif dan proses pengaturan yang sangat cepat.

## 📦 Fitur Utama

- **Layanan Lengkap:** Mendukung Apache, Nginx, MySQL, PHP, Redis, Memcached, MongoDB, PostgreSQL, Jupyter, dan banyak lagi.
- **Quick App:** Buat aplikasi Laravel, WordPress, atau framework lainnya hanya dengan satu klik.
- **Root Directory Fleksibel:** Anda dapat dengan mudah mengubah direktori proyek Anda.
- **Terminal Terintegrasi:** Dilengkapi dengan **Cmder** yang mendukung perintah Linux di Windows.
- **Mail Sender & Mail Catcher:** Fitur bawaan untuk menangkap email saat pengujian aplikasi tanpa perlu SMTP eksternal.

## 🛠️ Cara Menggunakan

1.  **Start All:** Tekan tombol "Start All" di UI Laragon untuk menjalankan servis (Apache/Nginx & MySQL).
2.  **Akses Web:** Buka browser dan ketik `localhost` untuk melihat dashboard Laragon.
3.  **Membuat Proyek Baru:**
    - Cukup buat folder baru di direktori `www` (contoh: `c:\laragon\www\nama-proyek`).
    - Laragon akan otomatis membuat virtual host `http://nama-proyek.test`.
4.  **Database:** Gunakan **HeidiSQL** (bawaan Laragon) atau **phpMyAdmin** untuk mengelola database.

## 📂 Struktur Direktori Standar

- `bin/`: Berisi biner aplikasi (PHP, MySQL, Apache, dll).
- `data/`: Lokasi penyimpanan data database.
- `etc/`: Konfigurasi aplikasi dan tools.
- `www/`: Direktori utama untuk proyek web Anda.
- `usr/`: Folder untuk menyimpan konfigurasi user dan data log.

---

**Developed with ❤️ for Modern Web Developers**
[Github Laragon](https://github.com/leokhoa/laragon) | [Official Website](https://laragon.org)
