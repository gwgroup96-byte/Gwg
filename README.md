# GWG Super App v3.0

Sistem Manajemen Konsinyasi — Generasi Wangi Group

## Update v3.0
1. ☁️ Sinkronisasi Real-Time (Firebase) — data otomatis tersinkron ke semua perangkat
2. 🟢 Ekspor Excel (.xlsx) — menggunakan SheetJS
3. 📄 Ekspor PDF Landscape — format profesional dengan header GWG
4. 🔐 Login Google — via Firebase Authentication

## Setup Firebase (Untuk Sinkronisasi)
1. Buka https://console.firebase.google.com
2. Buat project baru → Add web app
3. Salin config ke variabel FIREBASE_CONFIG di src/GWG_SuperApp.jsx
4. Aktifkan: Realtime Database (test mode) + Authentication (Google provider)

## Instalasi & Jalankan
```bash
npm install
npm run dev
```

## Deploy
- **Vercel**: `vercel --prod`
- **Netlify**: Drag folder `dist` setelah `npm run build`
