# 🚀 HABI STUDIO CODING .ZIP

**HABI STUDIO CODING .ZIP** adalah alat manajemen repository GitHub serbaguna yang berjalan sepenuhnya di browser (HP & desktop).  
Dibangun oleh **HABI STUDIO AI**, tool ini memungkinkan kamu mengelola file, folder, dan repository GitHub dengan cepat, tanpa perlu membuka GitHub secara manual.

---

## ✨ Fitur Utama

| Tab | Fungsi |
|-----|--------|
| 📄 **Single** | Cari file/folder (dengan path lengkap), muat kode, edit, dan upload. Cocok untuk update cepat. |
| 📦 **ZIP** | Upload file ZIP, otomatis diekstrak dan diupload ke repo dengan struktur yang sama. |
| ✏️ **Buat Baru** | Buat file baru langsung dari tool. Masukkan path lengkap (contoh: `repo/app/tools/file.tsx`), tulis kode, lalu simpan. Folder akan otomatis dibuat di GitHub. |
| 📂 **Files** | Jelajah seluruh isi repo, download file, hapus file/folder, hapus semua file, hapus repository. **Download Repository ZIP** dengan progress bar. |
| ✏️ **Rename** | Cari file/folder, otomatis terisi, ubah nama, lalu rename. |
| ➕ **Buat Repo** | Buat repository baru langsung dari tool. |
| 📋 **Daftar Repo** | Lihat semua repository milik akun, hapus massal dengan checkbox, riwayat penghapusan. Repo `deploy-tool` dilindungi. |
| 💬 **Chat to ZIP** | **Baru!** Tempel kode dari chat AI yang menggunakan penanda 📁. Tool akan otomatis membuat file ZIP dengan struktur folder yang sesuai. |

---

### 🆕 Update Terbaru

**Versi 2.0 — Mei 2025**

1. **💬 Chat to ZIP Converter**  
   Fitur revolusioner yang mengubah percakapan AI menjadi proyek siap pakai. Cukup tempel teks dari chat AI dengan penanda `📁` di setiap file, dan tool akan membungkusnya menjadi file ZIP yang siap diunduh. Bisa juga memasukkan link chat AI untuk diambil teksnya secara otomatis.

2. **📥 Download Repository ZIP**  
   Unduh seluruh isi repository sebagai file ZIP dengan progress bar real-time. Nama file dipertahankan asli (termasuk yang diawali titik seperti `.gitignore`). Notifikasi pop-up modern muncul saat download berhasil atau gagal.

3. **📊 Statistik Kode**  
   Setiap editor teks kini menampilkan jumlah karakter dan baris kode secara real-time, memudahkan kamu memantau ukuran kode yang sedang diedit.

4. **🎨 Animasi Logo**  
   Logo kustom kini memiliki efek shadow dinamis yang aktif selama 20 detik setiap 1 menit, memberikan sentuhan elegan pada tampilan tool.

5. **👥 Manajemen Akun Lebih Detail**  
   Tampilan akun kini menampilkan semua informasi: nama profil, username, repository, dan token (sebagian). Setiap field bisa dicopy dengan satu klik. Akun yang sedang aktif ditandai dengan badge ✅.

6. **🔔 Notifikasi Modern**  
   Semua notifikasi kini menggunakan UI modern (toast & modal), tidak ada lagi pop-up bawaan browser yang mengganggu.

7. **🎯 Quick Links**  
   Shortcut cepat ke **Chat → ZIP Converter** dan **GitHub Channel** tersedia di bagian atas tool.

---

### Fitur Tambahan Lainnya
- **Multi‑Akun**: Simpan banyak akun, lihat detail lengkap, switch tanpa logout, edit, dan copy informasi akun.
- **Info Repository Aktif**: Tool menampilkan repository mana yang sedang digunakan (`📁 Saat ini di repository: nama-repo`).
- **Pencarian Cepat**: Pencarian file/folder di berbagai tab dengan hasil langsung.
- **Pencarian Kode**: Cari teks di dalam editor dengan modal modern.
- **Tema Gelap/Terang**: Klik 🌓 untuk beralih tema.
- **Mode Anti‑Lag**: Matikan animasi latar belakang agar lebih ringan (default ON).
- **Logo Kustom**: Upload `logo.png` (200×55px) ke root repo untuk logo sendiri.
- **Efek Footer**: Teks footer memiliki efek gradasi warna yang indah.

---

## 📘 Panduan Penggunaan

### 1. Siapkan Token GitHub
Buat Personal Access Token (PAT) di [GitHub Settings → Developer settings → Tokens (classic)](https://github.com/settings/tokens/new?scopes=repo,delete_repo&description=HABI+STUDIO).  
Centang **repo** (wajib) dan **delete_repo** (untuk menghapus repo).

### 2. Buka Tool
Akses melalui GitHub Pages:  
🔗 **[https://habigeneratewebsite-a11y.github.io/deploy-tool/](https://habigeneratewebsite-a11y.github.io/deploy-tool/)**

### 3. Masukkan Kredensial
- Isi **Username GitHub**, **Repository Tujuan**, dan **Token Akses**.
- Klik **💾 Simpan** untuk menyimpan profil ke daftar akun.
- Gunakan tombol **👥 Akun** untuk mengelola banyak akun (simpan, pilih, edit, hapus).

### 4. Muat Struktur Repo
Klik **🔄 Muat Struktur** untuk memuat daftar file/folder dari repository yang aktif.

### 5. Gunakan Tab Sesuai Kebutuhan
- **📄 Single**: Cari file, muat, edit, upload.
- **📦 ZIP**: Unggah file ZIP.
- **✏️ Buat Baru**: Buat file baru dengan path lengkap.
- **📂 Files**: Jelajah, download, hapus, download ZIP repository.
- **✏️ Rename**: Cari & ubah nama file/folder.
- **➕ Buat Repo**: Buat repository baru.
- **📋 Daftar Repo**: Kelola & hapus massal repository.
- **💬 Chat to ZIP**: Tempel kode AI, dapatkan file ZIP.

---

## 💬 Cara Menggunakan Fitur Chat to ZIP

1. Buka tab **💬 Chat to ZIP**.
2. Tempelkan teks dari chat AI dengan format berikut:
   ```
   📁 frontend/pages/index.tsx
   import React from 'react';
   export default function Home() {
     return <div>Halo Dunia</div>;
   }

   📁 frontend/styles/global.css
   body {
     margin: 0;
     font-family: sans-serif;
   }

   📁 package.json
   {
     "name": "my-app",
     "version": "1.0.0"
   }
   ```
3. Klik **📦 Proses & Download ZIP**.
4. File ZIP akan terdownload dengan struktur folder yang sesuai.

**Alternatif**: Masukkan link chat AI di kolom yang tersedia, lalu klik **🌐 Ambil** untuk mengambil teksnya secara otomatis.

---

## 🎨 Logo Kustom

- Buat file `logo.png` dengan ukuran **200×55 piksel**.
- Upload ke root repository ini.
- Tool akan otomatis menampilkan logo tersebut dengan efek shadow dinamis.

---

## 🌍 Siapa yang Bisa Memakai?

✅ Siapa saja yang memiliki:
- Akun GitHub (gratis)
- Personal Access Token dengan izin `repo` dan `delete_repo`
- Repository target (milik sendiri atau kolaborator)

**Tidak perlu install apa pun.** Semua berjalan di browser.

---

## ⚠️ Keamanan

- Token hanya disimpan di `localStorage` browser kamu.
- Tool ini **sepenuhnya statis** (HTML/JS/CSS) tanpa backend.
- **Jangan bagikan token** ke orang lain.

---

## 🛠️ Teknologi

- HTML5, CSS3, JavaScript (Vanilla)
- [JSZip](https://stuk.github.io/jszip/) — library untuk membuat & mengekstrak ZIP
- GitHub API (REST v3)

---

## 📝 Lisensi

Proyek ini bebas digunakan dan dimodifikasi dengan tetap mencantumkan kredit ke **HABI STUDIO AI**.

---

**Powered by HABI STUDIO AI — Melampaui Batas Kreativitas**

🌐 **Website online**: [https://habigeneratewebsite-a11y.github.io/deploy-tool/](https://habigeneratewebsite-a11y.github.io/deploy-tool/)  
💬 **Riwayat pengembangan**: Tool ini dibuat dan disempurnakan melalui chat AI.  
📅 **Update terakhir**: Mei 2025
