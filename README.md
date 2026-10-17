# 🎓 Sevima EdLink Campus • Web & Mobile Official

Aplikasi digital kampus terpadu **Sevima EdLink** modern dengan arsitektur *mobile-first*, engine 3D holografik interaktif, sistem gamifikasi berbasis kecerdasan buatan (AI Verifier), dan kalender perkuliahan *real-time*.

![Version](https://img.shields.io/badge/version-4.9.10-07852a.svg)
![License](https://img.shields.io/badge/license-MIT-blue.svg)
![Deploy](https://img.shields.io/badge/deployed%20with-Vercel-black.svg)

---

## ✨ Fitur Utama

### 1. 🪪 Kartu 3D Holografik Mahasiswa & Dosen (Nama & NIM)
- **Sensor Gyroscope Interaktif**: Memiringkan smartphone secara fisik menggerakkan kartu dalam perspektif 3D (*pitch & roll*).
- **Parallax Kursor & Specular Glare**: Bergerak dinamis mengikuti kursor mouse di desktop dengan refleksi cahaya hologram emas-emerald.
- **Efek Goyang (Spring Wobble Physics)**: Di-tap atau diklik menghasilkan pantulan pegas elastis 5-tahap disertai *haptic feedback* getar.
- **Pameran XP & Rank**: Menampilkan live XP (misal `2.840 XP`), Level bintang, dan status keaktifan akademik.
- **Avatar Maskot Beo Tematik Jurusan**:
  - **S1 Teknik Informatika**: Cyber Hacker / Dev Visor HUD & Headphone `</>`.
  - **S1 Sistem Informasi**: Business Data Analyst ber-Kacamata Cerdas, Dasi Formal, dan grafik analitik.
  - **S1 Teknik Komputer**: Hardware & Robotics Specialist dengan Goggles, Antena & Sirkuit IoT.
  - **D3 Manajemen Informatika**: Creative Digital PM bertopi Baret Desainer & Bintang Emas.
  - **Dosen / Tenaga Pengajar**: Professor Beo bertoga akademik kehormatan beludru emas & medali dekan.
  - **Super Administrator (Root)**: Sovereign Beo bermahkota kekaisaran & kristal kuantum.

### 2. 🤖 AI Companion & Gamifikasi Cerdas
- **AI Vision Verifier Bukti Upload**: Mahasiswa dapat mengunggah tangkapan layar bukti Subscribe / Follow kanal resmi kampus (YouTube/Instagram/TikTok). AI Vision melakukan scan OCR 3-tahap otomatis dan memberikan hadiah **+200 XP & Koin**.
- **Repost dengan Tautan & Komentar**: Bagikan link repost media sosial dan sertakan ulasan reflektif. AI Companion mengevaluasi kedalaman konten komentar (analisis NLP) dan memberikan skor kualitas beserta bonus hingga **+250 XP**.
- **Leaderboard Real-time**: Peringkat kampus mahasiswa dengan podium trofi emas, perak, dan perunggu.

### 3. 📅 Real-Time Live Date & Interactive Calendar
- Berjalan otomatis sesuai tanggal sistem hari ini (`new Date()`).
- Kartu **Today's Schedule** di Home secara cerdas menampilkan mata kuliah hari ini. Di akhir pekan (Minggu), otomatis menampilkan panduan libur perkuliahan dan persiapan jadwal Senin.
- Kalender bulanan interaktif: klik tanggal mana saja untuk melihat mata kuliah dan ruangan pada tanggal tersebut.
- Tenggat tugas (deadline to-do) dihitung dinamis ke masa depan (selalu relevan).

### 4. 🖥️ Adaptasi Multi-Perangkat (HP, Tablet & Desktop)
- **Mode HP (440px)**: Tampilan native smartphone dengan dok navigasi bawah.
- **Mode Tablet (720px)**: Tampilan luas untuk iPad dan tablet.
- **Mode Desktop (980px)**: Tampilan web dashboard lengkap dengan tata letak dua kolom seimbang.
- Dilengkapi **Floating Device Bar** di layar laptop/desktop untuk berpindah tampilan seketika.

---

## 🚀 Panduan Push ke GitHub

Buka terminal PowerShell di folder ini, lalu jalankan:

```bash
# 1. Masuk ke direktori repositori
cd "C:\Users\SUDIONO\OneDrive\Dokumen\edlink-campus-web"

# 2. Hubungkan dengan GitHub Anda (Ganti dengan URL repo GitHub Anda)
git remote add origin https://github.com/<USERNAME-GITHUB-ANDA>/<NAMA-REPO-ANDA>.git

# 3. Pastikan branch utama bernama main
git branch -M main

# 4. Push ke GitHub
git push -u origin main
```

---

## ⚡ Panduan Deploy ke Vercel

### Opsi A: Deploy Langsung dari GitHub (Paling Direkomendasikan)
1. Buka [Vercel Dashboard](https://vercel.com/dashboard).
2. Klik **"Add New..."** → **"Project"**.
3. Hubungkan akun GitHub Anda dan pilih repositori `edlink-campus-web`.
4. Klik **"Deploy"** (Semua konfigurasi pada `vercel.json` otomatis terdeteksi).
5. Selesai! Website Anda langsung live dengan domain HTTPS gratis: `https://edlink-campus-web.vercel.app`.

### Opsi B: Deploy Menggunakan Vercel CLI
```bash
# Install Vercel CLI (jika belum ada)
npm i -g vercel

# Deploy langsung dari terminal
cd "C:\Users\SUDIONO\OneDrive\Dokumen\edlink-campus-web"
vercel --prod
```

---

## 🛠️ Tech Stack
- **Frontend**: Pure Vanilla HTML5, Modern CSS3 Flexbox & Grid, Vanilla ES6+ JavaScript (Zero external heavy frameworks).
- **3D Graphics**: Three.js WebGL Engine (Local with automatic CDN Fallback).
- **Icons & Graphics**: Pure Scalable Inline SVG Vector Graphics.
- **Deployment Target**: Vercel Serverless Edge Platform.

© 2026 Sevima EdLink Campus. All rights reserved.
