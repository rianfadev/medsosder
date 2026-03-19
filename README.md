# 🚀 Medsosder v12 by NEUMORIX - Script Termux Downloader Terlengkap

[![Python Version](https://img.shields.io/badge/Python-3.x-blue.svg)](https://python.org)
[![Termux Support](https://img.shields.io/badge/Termux-Supported-green.svg)](https://termux.dev)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

Apakah Anda mencari cara mudah untuk mengunduh video dan musik dari berbagai platform media sosial langsung melalui Termux Android? **Medsosder v12** adalah script Python open-source terbaik untuk kebutuhan Anda. 

Script ini dirancang khusus dengan antarmuka CLI yang interaktif (dilengkapi animasi loading *Hacker Style*) dan menggunakan `yt-dlp` serta `FFmpeg` untuk memastikan kualitas unduhan resolusi tertinggi secara otomatis.

## ✨ Fitur Utama
- 📥 **Unduh Video & Musik (MP3)** dengan kualitas terbaik (HD/4K jika tersedia).
- ⚙️ **Pemilihan Resolusi Cerdas:** Otomatis mendeteksi ukuran file dan resolusi yang tersedia pada link.
- 🎬 **Mendukung Multi-Platform:**
  - YouTube (Video & Shorts)
  - TikTok (Tanpa Watermark / Resolusi Asli)
  - Instagram (Reels, IGTV, Post)
  - Facebook (Watch & Reels)
  - Twitter / X
  - Snack Video
- 🔄 **Auto-Merge & Audio Extract:** Menggabungkan video dan audio secara mulus atau mengekstraknya murni menjadi file MP3 berkat dukungan FFmpeg.

---

## ⚠️ Disclaimer (Peringatan Penggunaan)
Alat ini dikembangkan murni untuk tujuan **edukasi dan pencadangan (backup) pribadi**. Pengguna bertanggung jawab penuh atas media yang diunduh menggunakan script ini. Kami tidak bertanggung jawab atas penyalahgunaan hak cipta. Pastikan Anda selalu mengunduh konten publik atau konten yang Anda miliki haknya.

---

## 📱 Cara Instalasi di Termux (Langkah demi Langkah)

Ikuti panduan di bawah ini. **Salin dan tempel (copy-paste) perintah di bawah ini SATU PER SATU** ke dalam aplikasi Termux Anda dan tekan Enter.

1. Berikan Termux izin untuk mengakses penyimpanan internal Anda. (PENTING: Akan muncul *pop-up* di layar HP Anda, pilih "Izinkan" atau "Allow"):
```bash
termux-setup-storage
