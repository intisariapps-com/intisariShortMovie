# 🎬 AutoVid Factory

> **Buat ratusan video pendek berkualitas tinggi — dari naskah hingga video jadi — dalam hitungan menit.**

AutoVid Factory adalah aplikasi desktop Windows yang mengotomatiskan seluruh proses produksi video pendek *faceless* (tanpa wajah), mulai dari pembuatan storyboard, pencocokan gambar AI, sinkronisasi voiceover, subtitle karaoke, hingga ekspor video final siap upload.

Cocok untuk kreator konten TikTok, YouTube Shorts, Instagram Reels, dan agensi media yang butuh produksi video massal secara efisien.

---

## ⚡ Apa yang Bisa Dilakukan AutoVid Factory?

| Tanpa AutoVid Factory | Dengan AutoVid Factory |
|---|---|
| Buat naskah manual, copy-paste satu per satu | Naskah diekstrak otomatis dari Gemini Chat |
| Generate gambar AI satu per satu di Google Flow | Gambar di-generate & diunduh otomatis |
| Cocokkan audio voiceover & gambar secara manual | Pencocokan audio-gambar dilakukan otomatis |
| Edit subtitle karaoke satu per satu | Subtitle karaoke dibuat otomatis per adegan |
| Proses 1 video = berjam-jam | Proses 1 video = hitungan menit |

---

## 🧩 Dua Komponen Utama

### 🌐 FlowAutoBridge — Ekstensi Chrome
Dipasang di Google Chrome, ekstensi ini bekerja di latar belakang untuk:
- Mengekstrak naskah storyboard dari Gemini Chat secara otomatis.
- Memasukkan instruksi visual dan mengklik generasi gambar di Google Flow secara otomatis.
- Mengunduh semua gambar hasil generasi langsung ke folder proyek Anda.

**Hasilnya:** Anda cukup memasukkan judul cerita ke Gemini — sisanya dikerjakan otomatis.

### 🖥️ AutoVid Factory — Aplikasi Desktop
Aplikasi utama yang mengambil alih setelah FlowAutoBridge selesai:
- Mendeteksi dan menyusun gambar, audio voiceover, dan naskah secara otomatis.
- Membuat subtitle karaoke animasi yang muncul kata per kata (mirip style kreator viral).
- Merender video dalam berbagai format: **9:16 (TikTok/Shorts)**, **16:9 (YouTube)**, dan **1:1 (Postingan)**.
- Menyimpan video final dengan satu klik ke folder pilihan Anda.

---

## 🖼️ Tampilan Aplikasi

Antarmuka modern berbasis web yang berjalan sebagai aplikasi desktop native — tidak perlu buka browser terpisah. Dilengkapi:
- **Panel proyek** untuk mengelola semua video Anda.
- **Progress bar** real-time saat rendering berlangsung.
- **Pemutar video** bawaan untuk preview sebelum menyimpan.
- **Notifikasi error** yang jelas dengan panduan solusi, bukan kode error yang membingungkan.

---

## 🔒 Lisensi

Saat ini aplikasi tersedia untuk **evaluasi bebas lisensi**. Sistem lisensi berbayar akan segera hadir dengan fitur-fitur tambahan eksklusif.

Rencananya mencakup:
- 🎙️ Akses suara AI premium (lebih natural, lebih ekspresif).
- 🎨 Lebih banyak template subtitle animasi eksklusif.
- 📤 Auto-upload langsung ke TikTok, YouTube Shorts, dan Reels.

---

## 💻 Kebutuhan Sistem

- **OS**: Windows 10 / 11 (64-bit)
- **RAM**: Minimal 8 GB
- **Storage**: 500 MB ruang kosong
- **Browser**: Google Chrome (untuk ekstensi FlowAutoBridge)

---

## 🚀 Cara Memulai

1. Unduh installer terbaru (`intisariShortMovie-Setup.exe`) dari tab **Releases** di halaman ini.
2. Jalankan Setup dan ikuti petunjuk instalasi.
3. Buka aplikasi → klik ikon **⚙️ Pengaturan** → masukkan API Key Groq Whisper Anda.
4. Pasang ekstensi **FlowAutoBridge** di Chrome dari folder `extension/` hasil instalasi.
5. Buka Gemini, buat storyboard, dan biarkan otomatisasi bekerja untuk Anda.
