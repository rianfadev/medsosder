# 🚀 Medsosder v12 by RianFa Dev - Script Termux Downloader Terlengkap

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
```
2. Perbarui sistem package Termux ke versi terbaru:
```bash
pkg update && pkg upgrade -y
```
3. Instal Git untuk mengunduh repository ini:
```bash
pkg install git -y
```
4. Instal bahasa pemrograman Python:
```bash
pkg install python -y
```
5. Instal FFmpeg (Sangat wajib agar script bisa mengekstrak musik MP3 dan menggabungkan resolusi video tinggi):
```bash
pkg install ffmpeg -y
```
6. Pindah ke folder Download di memori internal HP Anda. (Ini bertujuan agar script dan file yang diunduh langsung berada di folder Download HP Anda):
```bash
cd ~/storage/downloads
```
7. Instal modul library Python
```bash
pip install yt-dlp
```

## 🚀 Cara Menjalankan Script
Setelah semua langkah instalasi di atas berhasil dilakukan, Anda bisa menjalankan script ini kapan saja.
Buka Termux, lalu masuk ke folder script yang ada di folder Download Anda:
```bash
cd ~/storage/downloads
```
Kemudian jalankan script utamanya:
```bash
python medsosder-v13.py
```
(Catatan: Sesuaikan medsosder-v13.py dengan nama file asli Anda jika Anda mengubahnya).

## 🛠️ Tips & Troubleshooting
Error saat mendownload? Pastikan link yang Anda masukkan benar, lengkap dengan https://, dan pastikan akun/postingan target tidak di-private (harus publik).
Video tidak ada suaranya? Itu berarti Anda belum menginstal FFmpeg. Silakan jalankan kembali perintah pkg install ffmpeg -y.
Selalu perbarui yt-dlp: Sosial media sering memperbarui sistem keamanan mereka. Jika script tiba-tiba gagal mengunduh, perbarui modul dengan perintah:
```bash
pip install -U yt-dlp
```

## 📞 Kontak & Komunitas
Script ini dibuat secara independen. Jika Anda merasa terbantu, dukung pengembangan lebih lanjut melalui:
💬 Telegram: NEUMORIX
☕ Donasi: s.id/donate-neumorix
📅 Tanggal Rilis: 14 Maret 2026
Medsosder v12 - Dibuat dengan ♥︎ oleh NEUMORIX untuk Komunitas Open Source.









