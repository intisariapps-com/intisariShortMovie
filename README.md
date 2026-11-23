# 🎬 Intisari Short Movie

> **Buat ratusan video pendek berkualitas tinggi — dari naskah hingga video jadi — dalam hitungan menit.**

**Intisari Short Movie** adalah aplikasi desktop Windows yang mengotomatiskan seluruh proses produksi video pendek *faceless* (tanpa wajah), mulai dari pembuatan storyboard, pencocokan gambar AI, sinkronisasi voiceover, subtitle karaoke, hingga ekspor video final siap upload.

Cocok untuk kreator konten TikTok, YouTube Shorts, Instagram Reels, dan agensi media yang butuh produksi video massal secara efisien.

---

## ⚡ Apa yang Bisa Dilakukan Intisari Short Movie?

| Tanpa Intisari Short Movie | Dengan Intisari Short Movie |
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

### 🖥️ Intisari Short Movie — Aplikasi Desktop
Aplikasi utama yang mengambil alih setelah FlowAutoBridge selesai:
- Mendeteksi dan menyusun gambar, audio voiceover, dan naskah secara otomatis.
- Membuat subtitle karaoke animasi yang muncul kata per kata (mirip style kreator viral).
- Merender video dalam berbagai format: **9:16 (TikTok/Shorts)**, **16:9 (YouTube)**, dan **1:1 (Postingan)**.
- Menyimpan video final dengan satu klik ke folder pilihan Anda.

---

## 🎛️ Opsi Kualitas Render & Karakteristik Output

Aplikasi menyediakan fleksibilitas penuh dalam menentukan profil rendering sesuai kebutuhan produksi:

| Tipe Ekspor | Bitrate & Ukuran (6 Menit) | Karakteristik & Peruntukan |
|---|---|---|
| **1. Draft (Cepat & Ringan)** | ~3.000 kbps<br>**(±120 – 160 MB)** | **Resolusi tetap 1080p Full HD**, diproses dengan kompresi kilat (`preset ultrafast`). Sangat ideal untuk pratinjau cepat (*preview draft*), validasi alur cerita, atau perangkat dengan spesifikasi laptop hemat daya. |
| **2. HD 1080p (Potongan Langsung / Hard Cut)** | ~6.500 kbps<br>**(±250 – 290 MB)** | Profil mastering visual tajam maksimal dengan akselerasi GPU (Intel QSV, NVIDIA NVENC, AMD AMF) atau CPU CRF 19. Menghasilkan gambar *pixel-perfect* tanpa artefak buram, sangat kokoh untuk video dengan pergantian adegan cepat (*cut to cut*). |
| **3. HD 1080p (Transisi Sinematik Dynamic / Xfade)** | ~4.800 kbps<br>**(±200 – 220 MB)** | Menggunakan arsitektur *Hierarchical Chunked Engine* dengan transisi halus (*dissolve, slide, wipe, zoom*). **Mengapa ukuran file lebih ramping dari HD biasa?** Efek tumpang tindih (*overlap*) transisi antar adegan secara dinamis memadatkan kompresi frame tanpa mengurangi ketajaman visual sedikit pun, menghasilkan rasio ukuran yang sempurna agar video tidak dikompresi pecah oleh algoritma TikTok/Reels/Shorts. |

> 💡 **Fakta Resolusi:** Seluruh opsi di atas tetap menghasilkan video dengan resolusi kanvas penuh **1080p** sehingga rasio visual dan penempatan subtitle tidak pernah bergeser. Perbedaan ukuran semata-mata berasal dari laju kepadatan bit data (*bitrate*) dan gaya transisi yang dipilih.

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
