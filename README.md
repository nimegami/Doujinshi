# Doujinshi - Baca Manga & Doujin Bahasa Indonesia 📚

**[🌐 Preview Website](https://doujinshi.life)**

**Doujinshi.life** adalah platform website modern untuk membaca manga, manhwa, dan doujinshi dengan Bahasa Indonesia. Dibangun menggunakan **Node.js**, **Express**, dan **MongoDB**, proyek ini mengutamakan kecepatan, kenyamanan membaca (User Experience), dan desain yang responsif untuk perangkat mobile.

[![Preview Website](https://via.placeholder.com/1200x500?text=Klik+untuk+Membuka+Doujinshi.life)](https://doujinshi.life)

## ✨ Fitur Utama

### 🖥️ Frontend & User Experience
- **Lazy Loading Native**: Gambar chapter hanya dimuat ketika muncul di layar untuk menghemat kuota data.
- **Proteksi Gambar**: URL gambar disamarkan (obfuscated) menggunakan Base64 di sisi klien.
- **Immersive Reader**:
  - Sidebar daftar chapter (Drawer) yang responsif dan tidak mengganggu.
  - Navigasi **Next/Prev** pintar (mendukung chapter desimal/lompat).
  - *Tap-to-scroll* otomatis untuk kenyamanan membaca satu tangan.
- **Riwayat Baca (History)**: Menyimpan chapter terakhir yang dibaca secara otomatis menggunakan LocalStorage browser (tanpa perlu login).
- **Dark Mode UI**: Desain berbasis warna gelap yang nyaman di mata, dibangun dengan **Tailwind CSS**.

### ⚙️ Backend & Sistem
- **Optimasi Performa**: Menggunakan `Promise.all` untuk memuat data chapter, navigasi, dan sidebar secara paralel.
- **Manajemen Konten**:
  - Filter berdasarkan **Genre**, **Tipe** (Manga/Manhwa/Manhua), dan **Status**.
  - Hitung jumlah chapter otomatis per manga.
  - Pencarian real-time.
- **SEO Friendly**: Dilengkapi dengan Sitemap XML dinamis, meta tags Open Graph, dan struktur URL yang bersih.

## 🛠️ Teknologi

- **Runtime**: Node.js
- **Framework**: Express.js
- **Database**: MongoDB (dengan Mongoose ODM)
- **Templating**: EJS
- **Styling**: Tailwind CSS (CDN/Local)
- **Deployment**: Mendukung Vercel, Heroku, atau VPS (PM2).

## 🚀 Instalasi & Menjalankan (Lokal)

Pastikan Anda sudah menginstal **Node.js** dan memiliki koneksi **MongoDB**.

1. **Clone Repositori**
   ```bash
   git clone [https://github.com/username-anda/doujinshi-life.git](https://github.com/username-anda/doujinshi-life.git)
   cd doujinshi-life
   
