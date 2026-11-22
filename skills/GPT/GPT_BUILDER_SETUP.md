# Panduan Pemasangan di OpenAI ChatGPT / Custom GPT / Codex

### Mengapa File ZIP Gagal Diunggah ke ChatGPT Custom GPT?
OpenAI Custom GPTs (menu *Configure* -> *Knowledge*) adalah basis pengetahuan teks untuk pencarian dokumen (RAG).
OpenAI **TIDAK MENDUKUNG** pengunggahan file `.zip` bersarang sebagai ekstensi fungsional.

### Cara Memasang di ChatGPT Custom GPT (Rekomendasi Utama):
1. **Instruksi Asisten:**
   - Buka Custom GPT Editor (`chatgpt.com/gpts/editor`).
   - Masuk ke tab **Configure**.
   - Buka file `GPT_INSTRUCTIONS.md` (atau `skills/flow-storyboard-director/SKILL.md`), lalu salin (copy) seluruh isinya dan tempelkan (paste) ke kolom **Instructions**.
2. **Unggah Basis Pengetahuan (Knowledge):**
   - Di bagian **Knowledge**, klik *Upload files*.
   - Unggah file JSON gaya: `katalog_48_gaya_visual.json` (dapat diambil dari folder `skills/flow-storyboard-director/references/` atau diekstrak dari `01-flow-storyboard-director.zip`).
   - Unggah file referensi pendukung lainnya jika diperlukan (`cover-engine.md`, `character-mode.md`, `style-and-background.md`).
3. **Setelan Capabilities:**
   - Centang *Web Browsing* dan *DALL·E Image Generation* sesuai kebutuhan.
4. **Simpan / Publikasikan:**
   - Klik **Create** / **Update** di sudut kanan atas.

---

### Cara Memasang di OpenAI Codex / Plugin Developer:
- Jika Anda menggunakan antarmuka Codex Plugin developer yang mendukung manifest `.codex-plugin/plugin.json`, unggah langsung berkas **`00-complete.zip`**.
