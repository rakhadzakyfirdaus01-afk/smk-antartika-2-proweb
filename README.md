# Web Profil & PPDB SMK Antartika 2 Sidoarjo

Website profil sekolah dan Penerimaan Peserta Didik Baru (PPDB) SMK Antartika 2 Sidoarjo yang dirancang dengan arsitektur multi-halaman berbasis **HTML5** dan **CSS3 Flexbox murni**.

## 📌 Identitas Siswa
- **Nama:** Rakha Dzaky Firdaus
- **Kelas:** XI RPL 3
- **Mata Pelajaran:** Pemrograman Web (Bab 5 - Flexbox Layout)

---

## 🏫 Profil Singkat Sekolah
- **Nama Sekolah:** SMK Antartika 2 Sidoarjo
- **Status Akreditasi:** Terakreditasi "A"
- **Lokasi:** Jl. Siwalanpanji, Buduran, Sidoarjo, Jawa Timur
- **Fokus Keunggulan:** Sekolah Menengah Kejuruan Pusat Keunggulan di bidang Teknologi, Informatika, dan Bisnis Manajemen.

---

## 🎓 Program Keahlian / Jurusan
Website ini menampilkan 4 kompetensi keahlian utama:
1. **DKV (Desain Komunikasi Visual):** Desain grafis, ilustrasi digital, motion graphic, fotografi studio, branding visual, dan editing video.
2. **RPL (Rekayasa Perangkat Lunak):** Algoritma pemrograman, front-end & back-end web development, basis data MySQL/PostgreSQL, serta aplikasi mobile.
3. **TKJ (Teknik Komputer & Jaringan):** Infrastruktur jaringan, konfigurasi router Mikrotik & switch Cisco, instalasi Fiber Optic, dan administrasi Cloud Server.
4. **Akuntansi (Akuntansi & Keuangan Lembaga):** Pembukuan keuangan manual & komputerisasi (MYOB/Accurate), perpajakan, audit kas, dan simulasi Bank Mini.

---

## 🌐 Struktur Halaman Website (Multi-Page)
1. **`index.html` (Beranda / Home):**
   - Header & Navbar dengan badge Akreditasi A
   - Hero banner interaktif dengan ajakan mendaftar (CTA)
   - Ringkasan profil & statistik sekolah
   - Galeri kartu jurusan (DKV, RPL, TKJ, Akuntansi)
   - Pratinjau testimoni alumni
2. **`tentang.html` (Tentang Kami):**
   - Sejarah dan latar belakang SMK Antartika 2 Sidoarjo
   - Visi & Misi institusi
   - Fasilitas laboratorium unggulan (Lab Coding RPL, Lab Jaringan TKJ, Studio Multimedia DKV, Lab Bank Mini Akuntansi)
3. **`jurusan.html` (Kompetensi Keahlian):**
   - Penjelasan mendalam kurikulum, keahlian yang dipelajari, serta prospek karir/kerja tiap jurusan
4. **`testimoni.html` (Testimoni Alumni):**
   - Cerita sukses dan pengalaman karir alumni dari keempat jurusan
5. **`pendaftaran.html` (PPDB 2026 Online):**
   - Formulir pendaftaran calon siswa baru
   - Informasi persyaratan berkas, gelombang pendaftaran, dan kontak panitia
6. **`style.css`:**
   - Seluruh styling modern menggunakan CSS Flexbox terstruktur

---

## 💡 Penerapan Tantangan CSS Flexbox (Bab 5)
1. **`flex-wrap: wrap;` pada Navbar:**
   - Mencegah menu bertabrakan pada layar smartphone / tablet, menu membungkus ke baris berikutnya secara rapi.
2. **Variasi `justify-content`:**
   - `space-between`: Digunakan pada `.navbar` dan `.footer`.
   - `center`: Digunakan pada `.hero`, `.gallery`, dan `.testimoni-container`.
   - `space-around`: Diterapkan pada layout kartu pendukung dan navigasi.
3. **Section "Testimoni Alumni" Berbasis Flexbox:**
   - Menggunakan `display: flex; flex-direction: column;` di dalam kartu dan `flex-wrap: wrap;` pada kontainer.
4. **Mobile Responsiveness:**
   - Media query `@media (max-width: 640px)` memastikan seluruh elemen flexbox menyesuaikan tampilan layar HP secara proporsional.

---

## 🚀 Cara Menjalankan Website
1. Buka folder `C:\Users\rakha\Documents\smk antartika 2 proweb\` di File Explorer.
2. Klik dua kali pada `index.html` untuk membuka website di browser (Google Chrome, Microsoft Edge, dll).
3. Anda dapat menavigasi ke seluruh halaman melalui menu navbar di bagian atas.
