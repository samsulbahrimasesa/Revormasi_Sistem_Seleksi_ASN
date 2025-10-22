🤖 Aplikasi Seleksi ASN Prototype (Frontend Only)
🌟 Deskripsi Proyek
Ini adalah prototype aplikasi seleksi Calon Aparatur Sipil Negara (ASN) yang disimulasikan menggunakan teknologi frontend murni (HTML, CSS, JavaScript) dalam satu file. Proyek ini bertujuan untuk mendemonstrasikan alur pendaftaran, verifikasi wajah dengan kamera (simulasi proctoring), ujian berbasis komputer (Computer Assisted Test - CAT), dan fitur Portal Admin untuk memantau hasil peserta secara real-time.

Semua data (termasuk hasil ujian dan peringatan kecurangan) disimpan secara lokal di browser menggunakan localStorage dan hanya dapat dilihat melalui Portal Admin.

🛠️ Fitur Utama
Untuk Peserta
Registrasi & Upload Berkas: Formulir pendaftaran dan simulasi validasi upload file.

Verifikasi Wajah: Integrasi kamera browser untuk simulasi verifikasi biometrik sebelum ujian.

Ujian SKD (Simulasi): Panel ujian dengan contoh soal dan penghitungan skor sederhana.

AI Proctoring Simulation: Sensor kecurangan (kamera, audio, pindah tab) yang mencatat peringatan dan dapat mendiskualifikasi peserta.

Tampilan Hasil: Menampilkan skor SKD dan Integrity Index.

Untuk Administrator
Portal Admin Terpisah: Akses tersembunyi melalui tombol "Admin" di header.

Login Sederhana: Menggunakan password simulasi (1234).

Tampilan Data Peserta: Menampilkan Nama, NIK, Skor SKD, Integritas, dan jumlah Peringatan yang dicatat.

Simulasi Database: Menggunakan localStorage browser untuk menyimpan data hasil ujian secara persisten.

🚀 Cara Menjalankan
Proyek ini sangat mudah dijalankan karena tidak memerlukan server atau backend apa pun.

Unduh Kode: Salin seluruh kode HTML yang diberikan.

Simpan File: Buat file baru bernama index.html dan tempel (paste) kode di dalamnya.

Buka di Browser: Buka file index.html menggunakan web browser modern (Chrome, Firefox, Edge).

🔑 Akses Portal Admin
Masi tahap pengembangan

💡 Teknologi yang Digunakan
HTML5

CSS3 (Styling Inline & <style> block)

Vanilla JavaScript

localStorage: Digunakan sebagai simulasi database untuk menyimpan data peserta dan hasil ujian.

MediaDevices API: Digunakan untuk mengakses kamera dan mikrofon (permission diperlukan browser).

📄 Lisensi
Proyek prototype ini bersifat Unlicensed atau Public Domain. Anda bebas menggunakan, memodifikasi, dan mendistribusikannya untuk tujuan demonstrasi atau pembelajaran.
