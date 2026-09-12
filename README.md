## 📖 PANDUAN LENGKAP UNTUK MAHASISWA BARU TRPL 2026

Selamat datang di **GITUngu MPP 2026**! Ini adalah Buku Ungu versi digital standar industri **GitHub**. 

Jika Anda belum pernah menggunakan GitHub sebelumnya, **jangan khawatir!** Panduan ini dirancang khusus langkah demi langkah. Silakan baca dengan saksama dan ikuti alur kerjanya secara berurutan.

---

### 💡 1. Kenali Istilah Dasarnya Dulu!
* 📁 **Repository:** Folder proyek *private* milik kelompok Anda (`kelompok-XX`).
* 🌿 **Branch:** Jalur kerja pribadi Anda. Anda akan bekerja di branch privat Anda sendiri (`[NIM-Nama]`, contoh: `244311058-RiyanZakaria`).
* 💾 **Commit:** Untuk **"Menyimpan Perubahan"** teks atau berkas foto yang baru Anda tambahkan ke repository.
* 🔀 **Pull Request (PR):** Berkas pengajuan tugas terpusat tempat seluruh tugas Anda diperiksa dan tempat Panitia memberikan Tanda Tangan Digital (TTD).
* 📝 **Markdown (.md):** Format teks sederhana yang digunakan untuk menyusun biodata dan data penugasan.

---

### 🚀 2. Cara Masuk ke Dalam Tim Kelompok
1. **Tunggu Undangan Tim:** PJ Kelompok akan mengundang akun GitHub Anda ke dalam **`Team-Kelompok-XX`**.
2. **Cek Notifikasi / Email:** Buka email yang terhubung ke akun GitHub Anda, atau klik ikon lonceng (🔔) di pojok kanan atas halaman GitHub.
3. **Terima Undangan:** Klik tombol **Accept Invitation / Join Team**.  
   > 🎉 *Sekarang Anda resmi menjadi Member Organisasi dan memiliki hak akses untuk mengerjakan tugas di repo kelompok.*

---

### 🌿 3. Alur Kerja Buat Branch & Buka 1 Single PR

> [!IMPORTANT]
> **ATURAN GITUNGU:**  
> 1. Satu Mahasiswa = **Cukup membuat 1 Pull Request** dari awal sampai akhir.  
> 2. **DILARANG KERAS** melakukan *push* langsung ke branch `main`.  
> 3. **DILARANG** mengklik tombol *Merge pull request* sendiri sebelum ada instruksi resmi di hari terakhir.

#### Langkah Pembuatan:
1. Masuk ke repo kelompok Anda $\rightarrow$ Klik menu dropdown branch di kiri atas (yang bertuliskan **`main`**).
2. Ketik nama branch baru Anda dengan format: `[NIM-Nama]` *(Contoh: `244311058-RiyanZakaria`)* $\rightarrow$ Klik **Create branch: 240001-Ahmad from 'main'**.
3. Pastikan branch yang aktif di kiri atas sudah berganti ke **`[NIM-Nama]`** (contoh: `240001-Ahmad`).
4. Klik tab **Pull requests** di bagian atas $\rightarrow$ Klik tombol hijau **New pull request**.
5. Pastikan konfigurasi perbandingan branch:  
   * **`base: main`** $\leftarrow$ **`compare: [NIM-Nama]`** *(Contoh: `compare: 244311058-RiyanZakaria`)*
6. Klik **Create pull request**, isi judul PR dengan format:  
   `GITUngu 2026 [Nama Lengkap] - Kelompok-[XX]`
7. Klik **Create pull request** untuk menerbitkan PR.  
   > 📌 *Biarkan status Pull Request ini tetap **OPEN** sampai hari terakhir penugasan.*

---

### 📂 4. Menyiapkan Folder Pribadi & Mengerjakan Tugas

> [!WARNING]
> **BATAS AKSES:** Anda hanya boleh membuat dan mengedit file di dalam branch Anda sendiri yang telah dibuat sebelumnya. Dilarang keras menyentuh atau mengedit folder milik anggota kelompok lain!

1. Pastikan Anda selalu berada di branch Anda (`[NIM-Nama]`).
2. Masuk ke branch yang berisi berkas:
   * `01_BIODATA_PEMILIK.md`
   * `02_INTERAKSI_PANITIA.md` (Daftar 40 Panitia & Kolom TTD)
   * `03_INTERAKSI_ANGKATAN.md` (Daftar Mahasiswa Baru 1 Angkatan)
   * Sub-folder `assets/`
3. Buka file yang ingin dikerjakan $\rightarrow$ Klik ikon ✏️ **Pensil (Edit this file)**.
4. Ganti teks petunjuk di dalam kurung siku `[...]` dengan data asli.
5. **Simpan Perubahan (Commit):** Gulir ke bawah, tulis pesan commit yang rapi pada kolom *Commit message* dengan format `[deskripsi]`, lalu klik **Commit changes**.  
   *(Contoh: `isi biodata pemilik`, `update data interaksi panitia 01`)*.

---

### 🖼️ 5. Cara Mengunggah Foto Dokumentasi

Semua berkas foto wajib disimpan di dalam folder `assets/` pada branch Anda.

* **Syarat Foto:** Format foto, dan ukuran file **maksimal 200 KB**.
* **Cara Upload:**
  1. Buka folder `assets/` => /panitia untuk kebutuhan foto panitia, /maba untuk kebutuhan foto angkatan.
  2. Klik menu **Add file** $\rightarrow$ **Upload files**.
  3. (*drag & drop*) foto Anda ke halaman GitHub.
  4. Beri pesan commit: `upload foto panitia` $\rightarrow$ Klik **Commit changes**.
* **Menampilkan Foto di Markdown:**  
  Gunakan pemanggilan *relative path*: `<img src="assets/panitia/[nama_panggilan].[ext_foto]" alt="Description" style="object-fit:cover" width="300px" height="300px">`.

---

### ✍️ 6. Prosedur Meminta Tanda Tangan (TTD) Digital Panitia

1. **Syarat Sebelum ke Pos:** Sebelum mendatangi Pos Divisi, pastikan pada file `02_INTERAKSI_PANITIA.md` Anda sudah **minimal terisi Nama Lengkap & Divisi Panitia** yang bersangkutan.
2. **Saat di Pos:**
   * Lakukan interaksi dan foto bersama dengan Panitia.
   * Tunjukkan **Link Pull Request (PR)** atau QR Code PR milik Anda kepada Panitia.
3. **Proses TTD oleh Panitia:**
   * Panitia membuka link PR Anda lewat HP Panitia $\rightarrow$ Masuk ke tab **Files changed**.
   * Panitia mencari file `02_INTERAKSI_PANITIA.md` $\rightarrow$ Klik ikon **plus (+)** pada baris `<!-- TARGET_LINE_COMMENT_TTD_PANITIA_XX -->`.
   * Panitia mengetikkan format: `[SIGNED] [Nama_Panitia] - Divisi [Nama_Divisi]` $\rightarrow$ Panitia menekan tombol **Add single comment**.
4. **Penyempurnaan di Rumah:**
   * Sesampainya di rumah, unggah foto dokumentasi ke folder `assets/`.
   * Jika komentar TTD Panitia berubah status menjadi *Outdated* setelah Anda memperbarui foto atau data, **TTD tersebut tetap 100% SAH dan VALID** karena riwayatnya tersimpan permanen di tab *Conversation* PR Anda.
