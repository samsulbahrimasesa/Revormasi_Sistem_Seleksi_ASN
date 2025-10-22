# 🤖 Aplikasi Seleksi ASN Prototype (Frontend Only)

## 🌟 Deskripsi Proyek

Ini adalah *prototype* aplikasi seleksi Calon Aparatur Sipil Negara (ASN) yang disimulasikan menggunakan teknologi *frontend* murni (HTML, CSS, JavaScript) dalam satu file. Proyek ini bertujuan untuk mendemonstrasikan alur pendaftaran, verifikasi wajah, ujian berbasis komputer (Computer Assisted Test - CAT), dan fitur **Portal Admin** untuk memantau hasil peserta secara *real-time*.

Semua data (termasuk hasil ujian dan peringatan kecurangan) disimpan secara lokal di *browser* menggunakan **`localStorage`** dan hanya dapat dilihat melalui Portal Admin.

## 🛠️ Fitur Utama

### Untuk Peserta
* **Registrasi & Upload Berkas:** Formulir pendaftaran dan simulasi validasi *upload* file.
* **Verifikasi Wajah:** Integrasi kamera browser untuk simulasi verifikasi biometrik sebelum ujian.
* **Ujian SKD (Simulasi):** Panel ujian dengan contoh soal dan penghitungan skor sederhana.
* **AI Proctoring Simulation:** Sensor kecurangan (kamera, audio, pindah tab) yang mencatat peringatan dan dapat mendiskualifikasi peserta.
* **Tampilan Hasil:** Menampilkan skor SKD dan *Integrity Index*.

### Untuk Administrator
* **Portal Admin Terpisah:** Akses tersembunyi melalui tombol "Admin" di header.
* **Login Sederhana:** Menggunakan *password* simulasi (`1234`).
* **Tampilan Data Peserta:** Menampilkan **Nama**, **NIK**, **Skor SKD**, **Integritas**, dan jumlah **Peringatan** yang dicatat.
* **Simulasi Database:** Menggunakan **`localStorage`** browser untuk menyimpan data hasil ujian secara persisten.

## 🚀 Cara Menjalankan

Proyek ini sangat mudah dijalankan karena tidak memerlukan *server* atau *backend* apa pun.

1.  **Unduh Kode:** Salin seluruh kode HTML yang diberikan di jawaban sebelumnya.
2.  **Simpan File:** Buat file baru bernama **`index.html`** dan tempel (paste) kode di dalamnya.
3.  **Buka di Browser:** Buka file `index.html` menggunakan *web browser* modern (Chrome, Firefox, Edge).

## 🔑 Akses Portal Admin

Untuk menguji fitur admin:

masih dalam tahap pengembangan

Data peserta akan muncul di tabel setelah ada peserta yang menyelesaikan ujian.

## 💡 Teknologi yang Digunakan

| Teknologi | Kategori | Peran dalam Prototype |
| :--- | :--- | :--- |
| **HTML5, CSS3, Vanilla JS** | Dasar Frontend | Struktur, *styling*, dan logika utama aplikasi. |
| **`localStorage`** | Data Persistence | Simulasi *database* untuk menyimpan hasil ujian. |
| **MediaDevices API** | **Proctoring (Video/Audio)** | Mengakses **kamera** dan **mikrofon** untuk verifikasi dan pemantauan. |
| **Web Audio API** | **Proctoring (Audio)** | Menganalisis *input* **audio** (*noise level check*) untuk mendeteksi suara mencurigakan. |
| **Page Visibility API** | **Proctoring (Pindah Tab)** | Mendeteksi status halaman (*hidden* atau *visible*) untuk mencatat peringatan **pemindahan fokus** dari jendela ujian. |

## 📄 Lisensi

Proyek *prototype* ini bersifat **Unlicensed** atau **Public Domain**. Anda bebas menggunakan, memodifikasi, dan mendistribusikannya untuk tujuan demonstrasi atau pembelajaran.
