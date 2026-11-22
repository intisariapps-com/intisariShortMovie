# Paket Provider Gem_Custem (v2.8.7)

Setiap folder provider (`GPT/`, `Claude/`, `Gemini/`, `Antigravity/`) murni memuat berkas ZIP resmi dengan penamaan berakhiran versi (`*-v{version}.zip`):

| Berkas ZIP Resmi Berversi | Jenis & Peran | Versi Mandiri |
|---|---|---|
| `01-flow-storyboard-director-v3.0.0.zip` | Single-Skill (Flow & Intisari Storyboard Director) | `v3.0.0` |
| `02-realita-pov-scriptwriter-v2.0.0.zip` | Single-Skill (Realita POV Scriptwriter) | `v2.0.0` |
| `03-faceless-documentary-script-v2.0.0.zip` | Single-Skill (Faceless Documentary Scriptwriter) | `v2.0.0` |

- **Standar Murni Berversi**: Setiap berkas ZIP selalu memiliki nama versi di belakangnya (misal `01-flow-storyboard-director-v3.0.0.zip`). Tidak ada lagi alias file zip tanpa versi.
- **Preservasi Arsip**: Saat nomor versi di `version.json` dinaikkan dan di-build ulang, berkas versi lama tetap tersimpan utuh dan berkas versi baru akan otomatis dibuat.
- **Google Gemini Web ("Upload keahlian")**: Gunakan file `01-flow-storyboard-director-v*.zip`, `02-realita-pov-scriptwriter-v*.zip`, atau `03-faceless-documentary-script-v*.zip` (SKILL.md langsung di root tingkat pertama).
- **OpenAI GPT / Claude / Antigravity**: Unggah berkas ZIP berversi langsung ke antarmuka plugin masing-masing.
