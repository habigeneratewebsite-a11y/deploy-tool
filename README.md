# 🚀 HABI STUDIO CODING .ZIP

Website publik: https://habigeneratewebsite-a11y.github.io/deploy-tool/

Tool serba guna untuk mengelola repository GitHub langsung dari browser HP atau desktop. Dibangun oleh **HABI STUDIO AI**, tool ini memungkinkan kamu melakukan deploy kode dari chat AI, mengelola file, mengedit, merename, hingga menghapus repo hanya dengan satu klik.

## ✨ Fitur Utama

| Tab | Fungsi |
|-----|--------|
| 📄 **Single** | Upload satu file ke folder tertentu. Pilih folder dari dropdown, masukkan nama file, tempel kode, upload. |
| 📦 **ZIP** | Upload banyak file dari file ZIP. Seluruh struktur folder dipertahankan. |
| ✏️ **Editor** | Pilih file yang sudah ada, muat isinya, edit, lalu simpan kembali. |
| 📂 **Files** | Jelajah isi repo: download, hapus file, hapus folder, hapus semua file, atau hapus repository. |
| ✏️ **Rename** | Ubah nama file atau folder. Pilih item, masukkan path baru, rename. |

## 🛠️ Cara Menggunakan

1. **Siapkan Token GitHub**  
   Buat Personal Access Token (PAT) di [GitHub Settings > Developer settings > Personal access tokens > Tokens (classic)](https://github.com/settings/tokens/new?scopes=repo,delete_repo&description=HABI+STUDIO).  
   Centang **repo** (wajib) dan **delete_repo** (jika ingin fitur hapus repo).

2. **Buka Tool**  
   Akses melalui halaman GitHub Pages:  
   `https://habigeneratewebsite-a11y.github.io/deploy-tool/`  
   *(atau deploy tool ini di repositorimu sendiri)*.

3. **Masukkan Kredensial**  
   - Username GitHub  
   - Nama repository target (harus sudah ada)  
   - Token akses

4. **Muat Struktur Repo**  
   Klik tombol **Muat Struktur Repo**. Seluruh file dan folder akan muncul di tab yang relevan.

5. **Gunakan Fitur Sesuai Kebutuhan**  
   - Upload file tunggal atau ZIP.  
   - Edit file langsung.  
   - Jelajah, download, hapus, atau rename.  

## 🌍 Siapa yang Bisa Memakai?

Tool ini bisa dipakai oleh **siapa saja** yang memiliki:
- Akun GitHub (gratis)
- Personal Access Token dengan izin `repo` (baca/tulis konten) dan opsional `delete_repo` (untuk hapus repository)
- Repository target (milik sendiri atau sebagai kolaborator)

**Tidak perlu install apa pun.** Semua berjalan di browser. Data kredensial disimpan aman di localStorage perangkat masing-masing, tidak dikirim ke server lain selain api.github.com.

## ⚠️ Keamanan

- Token hanya disimpan di browser kamu (localStorage). Halaman ini statis dan tidak memiliki backend.  
- Selalu jaga kerahasiaan token. Jangan bagikan token ke orang lain.  
- Gunakan token dengan izin minimal yang diperlukan.

## 📝 Lisensi

Proyek ini dibuat untuk kemudahan pribadi dan dapat digunakan bebas. Modifikasi dan distribusi diperbolehkan dengan tetap mencantumkan kredit ke **HABI STUDIO AI**.

---

**Powered by HABI STUDIO AI — Melampaui Batas Kreativitas**
