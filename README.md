# Rutinitas & Latihan Harian

Aplikasi web (PWA) latihan otot dengan pembagian hari tetap dan pemulihan, koreksi postur bungkuk & peregangan, rutinitas pagi/sarapan/hidrasi, *power nap* 15–25 menit, tidur malam, notifikasi suara lembut & getar, serta pemain sesi latihan dengan penyetelan waktu manual.

## Struktur Folder
- `src/types/app.ts` — definisi tipe data jadwal, gerakan, dan rutinitas
- `src/data/programData.ts` — jadwal tetap Senin–Minggu, gerakan & koreksi postur, serta rutinitas harian
- `src/utils/timerAlerts.ts` — notifikasi suara lembut & getar saat timer selesai
- `src/App.tsx` — tampilan 4 layar utama & pemain sesi latihan
- `public/manifest.json` & `public/sw.js` — konfigurasi PWA & cache offline
- `.github/workflows/deploy.yml` — workflow otomatis ke GitHub Pages
