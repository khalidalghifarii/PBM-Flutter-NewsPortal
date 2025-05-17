# 📰 Flutter News Portal App

Proyek ini merupakan implementasi dari tugas mata kuliah **Pemrograman Berbasis Mobile (PBM)** dengan menggunakan framework **Flutter**. Aplikasi yang dibangun adalah sebuah portal berita sederhana yang memuat daftar berita, kategori, detail berita, serta fitur login dan registrasi pengguna.

## 👨‍🎓 Informasi Mahasiswa

- **Nama**: Muhammad Khalid Al Ghifari
- **NPM**: 2208107010044

## 📱 Deskripsi Aplikasi

Flutter News Portal App adalah aplikasi mobile sederhana yang menyediakan tampilan daftar berita terkini dari API eksternal (TechCrunch), serta menyediakan halaman login, registrasi, dan pengelompokan berdasarkan kategori.

Fitur utama:

- Menampilkan daftar berita dari API.
- Melihat detail isi berita.
- Kategori berita interaktif.
- Halaman login dan registrasi pengguna menggunakan _shared preferences_.
- Navigasi bawah dengan `CurvedNavigationBar`.

## 🛠️ Teknologi dan Package yang Digunakan

- **Flutter** & **Dart**
- **HTTP** (`http`) - untuk koneksi ke API berita dan autentikasi
- **Shared Preferences** (`shared_preferences`) - menyimpan data login lokal
- **Fluttertoast** - menampilkan notifikasi toast
- **Curved Navigation Bar** (`curved_navigation_bar`) - navigasi bagian bawah aplikasi

## 📂 Struktur Folder Penting

```

lib/
├── detail.dart         // Halaman detail berita
├── formlogin.dart      // Form login
├── formregist.dart     // Form registrasi
├── home.dart           // Halaman utama berita
├── kategori.dart       // Halaman kategori berita
├── main.dart           // Entry point aplikasi
├── profil.dart         // Halaman profil

```

## 🚀 Cara Menjalankan Proyek

1. Clone repositori ini:

   ```bash
   git clone https://github.com/khalidalghifarii/PBM-Flutter-NewsPortal.git
   cd PBM-Flutter-NewsPortal
   ```

2. Install dependencies:

   ```bash
   flutter pub get
   ```

3. Jalankan aplikasi:

   ```bash
   flutter run
   ```

---
