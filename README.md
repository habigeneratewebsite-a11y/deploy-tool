# 🚀 HABI STUDIO CODING .ZIP

**HABI STUDIO CODING .ZIP** adalah tool manajemen repository GitHub serbaguna yang berjalan langsung di browser (HP/desktop).  
Dibangun oleh **HABI STUDIO AI**, tool ini memungkinkan kamu mengelola file, folder, dan repository GitHub dengan mudah, cepat, dan tanpa ribet.

## ✨ Fitur Utama

| Tab | Fungsi |
|-----|--------|
| 📄 **Single** | Cari file/folder (dengan path lengkap), muat kode, edit, dan upload. Cocok untuk update cepat. |
| 📦 **ZIP** | Upload file ZIP, otomatis diekstrak dan diupload ke repo dengan struktur yang sama. |
| ✏️ **Editor** | Cari file, muat, edit dengan fitur cari & ganti teks, lalu simpan kembali. |
| 📂 **Files** | Jelajah seluruh isi repo, download file, hapus file/folder, hapus semua file, hapus repository. |
| ✏️ **Rename** | Cari file/folder, otomatis terisi, ubah nama, lalu rename. |
| ➕ **Buat Repo** | Buat repository baru langsung dari tool. |
| 📋 **Daftar Repo** | Lihat semua repository milik akun, hapus massal dengan checkbox, riwayat penghapusan. Repo `deploy-tool` dilindungi. |

### Fitur Tambahan
- **Multi‑Akun**: Simpan banyak akun GitHub, switch tanpa logout, edit kredensial.
- **Pencarian Cepat**: Pencarian file/folder di berbagai tab dengan hasil langsung.
- **Pencarian Kode**: Cari teks di dalam editor dengan modal modern (bukan prompt bawaan).
- **Tema Gelap/Terang**: Klik 🌓 untuk beralih tema.
- **Mode Anti‑Lag**: Matikan animasi latar belakang agar lebih ringan.
- **Logo Kustom**: Upload `logo.png` (200×55px) ke root repo untuk logo sendiri.
- **Efek Footer**: Teks footer memiliki efek gradasi, dan efek kilau muncul setiap 3 jam (pertama setelah 20 detik).

## 📘 Panduan Penggunaan

1. **Siapkan Token GitHub**  
   Buat Personal Access Token (PAT) di [GitHub Settings → Developer settings → Tokens (classic)](https://github.com/settings/tokens/new?scopes=repo,delete_repo&description=HABI+STUDIO).  
   Centang **repo** (wajib) dan **delete_repo** (untuk menghapus repo).

2. **Buka Tool**  
   Akses melalui GitHub Pages:  
   `https://habigeneratewebsite-a11y.github.io/deploy-tool/`

3. **Masukkan Kredensial**  
   Isi username GitHub, nama repository target, dan token.  
   Klik tombol **Simpan** (💾) untuk menyimpan profil.  
   Bisa menyimpan banyak akun dan beralih lewat tombol **👥 Akun**.

4. **Muat Struktur Repo**  
   Klik **🔄 Muat Struktur** untuk memuat daftar file/folder.  
   Setelah itu, semua tab siap digunakan.

5. **Gunakan Tab Sesuai Kebutuhan**  
   - **Single/Editor**: Cari file, muat, edit, upload.  
   - **ZIP**: Unggah file ZIP.  
   - **Files**: Jelajah, download, hapus.  
   - **Rename**: Cari, rename.  
   - **Buat Repo**: Buat repository baru.  
   - **Daftar Repo**: Kelola semua repository.

## 🎨 Logo Kustom

Kamu bisa mengganti logo default dengan logo sendiri:
- Buat file `logo.png` dengan ukuran **200×55 piksel** (atau proporsional, maksimal lebar 200px).
- Upload ke root repository ini (klik **Add file → Upload files**).
- Tool akan otomatis menampilkan logo tersebut. Jika file tidak ditemukan, logo SVG bawaan akan muncul.

## 🌍 Siapa yang Bisa Memakai?

Tool ini bisa dipakai oleh **siapa saja** yang memiliki:
- Akun GitHub (gratis)
- Personal Access Token dengan izin `repo` (baca/tulis) dan `delete_repo` (untuk hapus repo)
- Repository target (milik sendiri atau kolaborator)

Tidak perlu install apa pun. Semua berjalan di browser. Data kredensial disimpan aman di `localStorage` perangkat masing‑masing.

## ⚠️ Keamanan

- Token hanya disimpan di browser kamu, tidak dikirim ke server selain `api.github.com`.
- Tool ini sepenuhnya statis (HTML/JS/CSS) tanpa backend.
- Jangan bagikan token ke orang lain. Gunakan token dengan izin minimal yang diperlukan.

## 🛠️ Teknologi

- HTML5, CSS3, JavaScript (Vanilla)
- [JSZip](https://stuk.github.io/jszip/) untuk ekstrak ZIP di browser
- GitHub API (REST v3)

## 📝 Lisensi

Proyek ini dibuat untuk kemudahan pribadi dan dapat digunakan bebas. Modifikasi dan distribusi diperbolehkan dengan tetap mencantumkan kredit ke **HABI STUDIO AI**.

---

**Powered by HABI STUDIO AI — Melampaui Batas Kreativitas**

Website online siap digunakan: https://habigeneratewebsite-a11y.github.io/deploy-tool/

Website edit prompt tool ini : https://chat.deepseek.com/share/pc40l0zpri33qa9x2c
