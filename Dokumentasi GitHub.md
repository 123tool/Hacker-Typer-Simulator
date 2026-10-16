# 🖥️ Hacker Typer Simulator (Clone)

Simulator peretasan (*hacking*) interaktif bergaya terminal retro ala Hollywood / Matrix. Aplikasi berbasis web ini dirancang khusus sebagai **properti film/teater**, **sarana lelucon (prank) teman**, atau sekadar membuat Anda terlihat **super sibuk di kantor maupun ruang kelas**.

---

## 📌 Nama Repository GitHub (Direkomendasikan)

Saat membuat repository baru di GitHub, gunakan nama berikut:
`hacker-typer-clone` atau `hacker-typer-simulator`

---

## 🚀 Fitur Utama

1. **Simulasi Ketikan Otomatis Cerdas:**
   * Setiap kali Anda menekan tombol apapun di keyboard, sistem akan memunculkan 3 hingga 5 karakter dari kode pemrograman tingkat tinggi (Kernel C++, Python Crypto, Enkripsi AES JS).
2. **Efek Visual Retro / CRT Terminal:**
   * Tampilan serba hitam pekat dengan warna teks hijau neon (`#00ff00`), font *monospaced* 'Fira Code', serta efek garis pemindai CRT (*scanline*) jadul.
3. **Suara Ketikan Keyboard Mekanik Real-Time:**
   * Menggunakan **Web Audio API** bawaan browser untuk memutar efek suara *synthesizer* tombol mekanik secara dinamis di setiap ketukan tanpa tergantung file audio eksternal.
4. **Pintasan Keyboard Rahasia (Fitur Utama Prank):**
   * **`Alt` (Tekan 3x Berturut-Turut):** Memicu tampilan layar *glitch* hijau bertuliskan **ACCESS GRANTED**.
   * **`CapsLock` (Tekan 3x Berturut-Turut):** Memicu peringatan darurat merah berkedip bertuliskan **ACCESS DENIED**.
   * **`Esc`:** Menutup kotak dialog/peringatan aktif dan mengembalikan fokus ke terminal.
   * **`F11`:** Mode Layar Penuh (*Fullscreen*).
5. **Dukungan Perangkat Mobile / Layar Sentuh:**
   * Dilengkapi bilah kontrol virtual dan input transparan agar pengguna smartphone/tablet dapat ikut mengetik kode dengan lancar.

---

## 📁 Struktur File Proyek

Proyek ini menggunakan struktur web standar yang rapi dan mudah dikembangkan:

```text
hacker-typer-clone/
├── index.html       # Struktur HTML5 utama
├── style.css        # Gaya visual terminal retro & efek CRT
├── script.js        # Logika simulator ketikan & pintasan keyboard
└── README.md        # Dokumentasi resmi proyek (file ini)
```

---

## 🛠️ Cara Menjalankan Secara Lokal

1. Unduh atau *clone* repository ini ke komputer Anda:
   ```bash
   git clone https://github.com/USERNAME/hacker-typer-clone.git
   ```
2. Buka folder proyek.
3. Klik dua kali pada file `index.html` untuk membuanya langsung di web browser pilihan Anda (Chrome, Firefox, Edge, Safari).

---

## 🌐 Panduan Deployment Gratis di GitHub Pages (Langkah demi Langkah)

Ikuti langkah-langkah mudah di bawah ini untuk mempublikasikan website simulator Anda ke internet secara gratis:

### Langkah 1: Buat Repository Baru di GitHub
1. Buka dan *login* ke akun [GitHub](https://github.com/).
2. Di pojok kanan atas, klik ikon **+** lalu pilih **New repository**.
3. Isi **Repository name** dengan: `hacker-typer-clone`.
4. Pilih visibilitas **Public** (wajib agar GitHub Pages gratis dapat diakses umum).
5. Jangan centang *Add a README file* jika Anda ingin mengunggah file yang sudah ada.
6. Klik tombol **Create repository**.

### Langkah 2: Unggah Berkas Kode Sumber
1. Pada halaman repository yang baru dibuat, klik link **uploading an existing file**.
2. Seret (*drag & drop*) seluruh file proyek Anda (`index.html`, `style.css`, `script.js`, dan `README.md`).
3. Pada bagian bawah (*Commit changes*), isi pesan singkat seperti `Initial commit`.
4. Klik tombol hijau **Commit changes**.

### Langkah 3: Aktifkan Fitur GitHub Pages
1. Masuk ke tab **Settings** (ikon roda gigi) di dalam repository Anda.
2. Pada menu navigasi sebelah kiri (kategori *Code and automation*), klik **Pages**.
3. Pada bagian **Build and deployment**:
   * **Source**: Pilih `Deploy from a branch`.
   * **Branch**: Pilih `main` (atau `master`) dan pastikan foldernya diset ke `/ (root)`.
4. Klik tombol **Save**.

### Langkah 4: Website Siap Diakses!
* Tunggu sekitar 1–2 menit hingga GitHub selesai memproses *deployment*.
* Refresh halaman *Settings > Pages*. Anda akan melihat kotak berwarna hijau dengan tautan situs Anda, contohnya:
  `https://username.github.io/hacker-typer-clone/`
* Salin tautan tersebut dan bagikan ke teman-teman Anda!

---

## 💡 Tips Penggunaan Saat Prank
* **Aktifkan Fullscreen:** Tekan tombol **F11** di keyboard agar tampilan browser memenuhi seluruh layar laptop/komputer tanpa terlihat address bar.
* **Mulai Mengetik:** Letakkan tangan Anda di atas keyboard