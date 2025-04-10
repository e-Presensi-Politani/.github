# 📌 e-Presensi Politani

Aplikasi absensi berbasis web untuk lingkungan kampus **Politeknik Pertanian Negeri Payakumbuh**. Sistem ini mendukung presensi dosen dan ASN dengan fitur **Geo-fencing**, selfie, pengajuan izin/cuti, dan laporan statistik kehadiran.

---

## 🚀 Fitur Utama

- ✅ Autentikasi pengguna (login berbasis role)
- 📍 Geo-fencing untuk validasi lokasi absensi
- 📸 Absensi dengan selfie (kamera)
- 📅 Pengajuan cuti, izin (terlambat, cepat pulang, dsb)
- ⏰ Perhitungan jam kerja otomatis (wajib 8.5 jam/hari)
- 📊 Statistik & histori kehadiran per dosen
- 📥 Export laporan ke PDF / Excel
- 🔔 Notifikasi & reminder absensi

---

## ⚙️ Teknologi yang Digunakan

### Backend:
- [NestJS](https://nestjs.com/)
- [TypeORM](https://typeorm.io/)
- [MySQL](https://www.mysql.com/)
- [@nestjs/config](https://docs.nestjs.com/techniques/configuration) untuk manajemen `.env`

### Frontend (rencana):
- React + Bootstrap

---

## 🧪 Cara Menjalankan (Development)

### 1. Clone Repo

```bash
git clone https://github.com/username/e-presensi.git
cd e-presensi
