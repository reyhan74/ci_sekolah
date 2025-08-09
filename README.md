# CI_Sekolah

Aplikasi manajemen sekolah berbasis **CodeIgniter** (PHP Framework ringan) untuk mengelola data siswa, guru, dan administrasi lainnya.

## 📌 Fitur Utama
- Dashboard admin dan operator.
- Manajemen data siswa: tambah, edit, hapus.
- Manajemen data guru dan staf.
- Input dan pengelolaan nilai siswa.
- Penjadwalan kelas dan pelajaran.
- Laporan akademik (nilai, daftar hadir, dll).
- Autentikasi login berbasis peran (admin, operator, guru).

## 📂 Struktur Direktori
```
ci_sekolah/
├── application/        # Core CI (controllers, models, views)
│   ├── controllers/
│   ├── models/
│   └── views/
├── system/              # Sistem CodeIgniter
├── assets/              # CSS, JS, gambar, plugin frontend
├── public/              # Entry point (index.php, assets publik)
├── .env / .htaccess     # Pengaturan environment & routing
└── README.md            # Dokumentasi proyek
```

## ⚙️ Instalasi & Setup
1. Clone repo:
   ```bash
   git clone https://github.com/reyhan74/ci_sekolah.git
   ```
2. Jalankan:
   - Untuk CodeIgniter 4:
     ```bash
     composer install
     cp env .env
     ```
   - Untuk CodeIgniter 3, pastikan folder `application` dan `system` berada di root project.
3. Buat database baru di MySQL (misalnya `ci_sekolah`).
4. Sesuaikan konfigurasi database:
   - **CI4**: di `.env` (atur `database.default.*`)
   - **CI3**: di `application/config/database.php`
5. Jalankan migrasi (jika tersedia):
   ```bash
   php spark migrate
   ```
6. Akses aplikasi di browser:
   ```
   http://localhost/ci_sekolah/public/
   ```

## 🔑 Login Administrator
- **Username**: `admin`
- **Password**: `admin123`
  
*(Ubah kredensial pada konfigurasi untuk keamanan.)*

## 🖥️ Demo Online
*Jika tersedia, masukkan link demo di sini (opsional).*

## 🤝 Kontribusi
Jika kamu ingin berkontribusi:
1. Fork repo ini.
2. Buat fitur baru atau perbaikan pada branch baru.
3. Ajukan Pull Request (PR) dan jelaskan perubahan yang dilakukan.

## 📜 Lisensi
Lisensi MIT © Tahun 2025 Reyhan

---

**Dibuat oleh**: Reyhan  
**Tahun**: 2025
