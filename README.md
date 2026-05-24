# 🚀 HABI STUDIO CODING .ZIP

**HABI STUDIO CODING .ZIP** adalah alat manajemen repository GitHub serbaguna yang berjalan sepenuhnya di browser (HP & desktop).  
Dibangun oleh **HABI STUDIO AI**, tool ini memungkinkan kamu mengelola file, folder, dan repository GitHub dengan cepat, tanpa perlu membuka GitHub secara manual.

## ✨ Fitur Utama

| Tab | Fungsi |
|-----|--------|
| 📄 **Single** | Cari file/folder (dengan path lengkap), muat kode, edit, dan upload. Cocok untuk update cepat. |
| 📦 **ZIP** | Upload file ZIP, otomatis diekstrak dan diupload ke repo dengan struktur yang sama. |
| ✏️ **Buat Baru** | **Baru!** Buat file baru langsung dari tool. Masukkan path lengkap (contoh: `repo/app/tools/file.tsx`), tulis kode, lalu simpan. Folder akan otomatis dibuat di GitHub. |
| 📂 **Files** | Jelajah seluruh isi repo, download file, hapus file/folder, hapus semua file, hapus repository. |
| ✏️ **Rename** | Cari file/folder, otomatis terisi, ubah nama, lalu rename. |
| ➕ **Buat Repo** | Buat repository baru langsung dari tool. |
| 📋 **Daftar Repo** | Lihat semua repository milik akun, hapus massal dengan checkbox, riwayat penghapusan. Repo `deploy-tool` dilindungi. |

### Fitur Tambahan
- **Multi‑Akun**: Simpan banyak akun, lihat detail lengkap (nama profil, username, repo, token), switch tanpa logout, edit, dan copy informasi akun.
- **Info Repository Aktif**: Tool menampilkan repository mana yang sedang digunakan.
- **Pencarian Cepat**: Pencarian file/folder di berbagai tab dengan hasil langsung.
- **Pencarian Kode**: Cari teks di dalam editor dengan modal modern.
- **Tema Gelap/Terang**: Klik 🌓 untuk beralih tema.
- **Mode Anti‑Lag**: Matikan animasi latar belakang agar lebih ringan (default ON).
- **Logo Kustom**: Upload `logo.png` (200×55px) ke root repo untuk logo sendiri.
- **Efek Footer**: Teks footer memiliki efek gradasi, dan efek kilau muncul setiap 3 jam (pertama setelah 20 detik).
- **Quick Links**: Shortcut ke Chat → ZIP converter dan GitHub Channel.

## 📘 Panduan Penggunaan

1. **Siapkan Token GitHub**  
   Buat Personal Access Token (PAT) di [GitHub Settings → Developer settings → Tokens (classic)](https://github.com/settings/tokens/new?scopes=repo,delete_repo&description=HABI+STUDIO).  
   Centang **repo** (wajib) dan **delete_repo** (untuk menghapus repo).

2. **Buka Tool**  
   Akses melalui GitHub Pages:  
   `https://habigeneratewebsite-a11y.github.io/deploy-tool/`

3. **Masukkan Kredensial**  
   Isi username GitHub, nama repository target, dan token.  
   Klik tombol **💾 Simpan** untuk menyimpan profil.  
   Bisa menyimpan banyak akun dan beralih lewat tombol **👥 Akun**.

4. **Muat Struktur Repo**  
   Klik **🔄 Muat Struktur** untuk memuat daftar file/folder.  
   Setelah itu, semua tab siap digunakan.

5. **Gunakan Tab Sesuai Kebutuhan**  
   - **Single**: Cari file, muat, edit, upload.  
   - **ZIP**: Unggah file ZIP.  
   - **Buat Baru**: Buat file baru dengan path lengkap, otomatis struktur folder dibuat.  
   - **Files**: Jelajah, download, hapus.  
   - **Rename**: Cari, rename.  
   - **Buat Repo**: Buat repository baru.  
   - **Daftar Repo**: Kelola semua repository.

## 🎨 Logo Kustom

Kamu bisa mengganti logo default dengan logo sendiri:
- Buat file `logo.png` dengan ukuran **200×55 piksel** (atau proporsional, maksimal lebar 200px).
- Upload ke root repository ini (klik **Add file → Upload files**).
- Tool akan otomatis menampilkan logo tersebut. Jika file tidak ditemukan, area logo kosong.

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

🌐 **Website online**: [https://habigeneratewebsite-a11y.github.io/deploy-tool/](https://habigeneratewebsite-a11y.github.io/deploy-tool/)  
💬 **Edit/prompt tool ini**: [https://chat.deepseek.com/a/chat/s/af7943c8-9481-4b7b-9141-026950462aaa](https://chat.deepseek.com/a/chat/s/af7943c8-9481-4b7b-9141-026950462aaa)
