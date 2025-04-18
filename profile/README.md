# 📌 e-Presensi Politani

Aplikasi presensi berbasis web untuk lingkungan kampus **Politeknik Pertanian Negeri Payakumbuh**. Sistem ini mendukung presensi dosen dengan fitur **Geo-fencing**, selfie, mode kerja fleksibel (WFH/WFA/DL), pengajuan izin/cuti, dan laporan statistik kehadiran.

## 🚀 Fitur Utama

- ✅ **Autentikasi pengguna** - Login berbasis role (Admin, Ketua Jurusan, Dosen)
- 📍 **Geo-fencing** - Validasi lokasi presensi untuk mode kerja di kampus
- 📸 **Presensi dengan selfie** - Verifikasi kehadiran melalui foto
- 🏠 **Mode kerja fleksibel** - Dukungan untuk WFH (Work From Home), WFA (Work From Anywhere), dan DL (Dinas Luar)
- 📋 **Manajemen koreksi presensi** - Form koreksi untuk kasus lupa check-in/check-out dengan persetujuan Ketua Jurusan
- 📅 **Pengajuan izin/cuti** - Sistem pengajuan dan persetujuan izin kerja
- ⏰ **Perhitungan jam kerja otomatis** - Verifikasi pemenuhan jam kerja wajib (8.5 jam/hari)
- 📊 **Statistik & histori kehadiran** - Laporan kehadiran per dosen dan per jurusan
- 📥 **Export laporan** - Konversi laporan ke format PDF/Excel

## 👥 Role Pengguna

- **Admin** - Mengelola pengguna, jurusan, dan konfigurasi sistem
- **Ketua Jurusan** - Mengelola anggota jurusan, menyetujui koreksi dan izin, akses laporan jurusan
- **Dosen** - Melakukan check-in/check-out, mengajukan koreksi dan izin, melihat histori kehadiran

## ⚙️ Teknologi yang Digunakan

### Backend:
- [NestJS](https://nestjs.com/) - Framework Node.js untuk backend
- [MongoDB](https://www.mongodb.com/) - Database NoSQL
- [Mongoose](https://mongoosejs.com/) - ODM untuk MongoDB

### Frontend (rencana):
- [React](https://reactjs.org/) - Library JavaScript untuk UI
- [Bootstrap](https://getbootstrap.com/) - Framework CSS untuk desain responsive

## 🗂️ Struktur Proyek

```
src/
├── main.ts                            # Entry point aplikasi
├── app.module.ts                      # Modul utama aplikasi
├── config/                            # Konfigurasi aplikasi
├── users/                             # Modul pengguna
├── auth/                              # Modul autentikasi
├── attendance/                        # Modul presensi
├── departments/                       # Modul jurusan
├── leave-requests/                    # Modul izin/cuti
├── reports/                           # Modul laporan
└── common/                            # Utilitas dan komponen bersama
```

## 📊 Skema Database

Sistem menggunakan MongoDB dengan schema utama:
- User
- Department
- Attendance
- LeaveRequest
- AttendanceStatistics

## 👨‍💻 Pengembang

- M. Ghozi Syah Putra
- ghozi286@gmail.com
