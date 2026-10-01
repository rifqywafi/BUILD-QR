# Build QR - 3D Building QR Generator

Build QR adalah sebuah aplikasi web interaktif yang mengubah teks atau URL biasa menjadi sebuah QR Code berbentuk kota 3D (Isometric City). Aplikasi ini memungkinkan Anda membuat QR Code yang unik, memukau secara visual, namun tetap dipertahankan fungsionalitasnya 100% agar dapat dibaca oleh scanner QR.

---

## Fitur Utama

- Real-Time 3D Generation: Ketik teks/URL apa pun dan sistem akan langsung membangun blok-blok kota 3D yang merepresentasikan matriks QR Code.
- 3 Tema Visual Mendalam: Pilihan tema yang merombak total tampilan visual, model bangunan, palet warna, dan lingkungan sekitar (environment).
- Top-Down Scan Mode: Transisi animasi kamera yang mulus dari tampilan diorama 3D (isometric) ke tampilan atas tegak lurus (2D) agar QR Code dapat di-scan.
- Instant Download: Satu klik untuk mengunduh gambar murni QR Code tampak atas (bebas hambatan visual) sebagai file PNG.
- Sistem Pengacakan (Regenerate): Tombol "Acak" yang men-shuffle posisi warna, memvariasikan tinggi gedung, dan merombak detail lingkungan tanpa merusak pola matriks QR itu sendiri.

---

## Penjelasan Tema (Themes)

1. Metropolis (Modern City)
   - Kota beton modern bernuansa slate dan navy.
   - Gedung pencakar langit berlantai banyak dengan jendela menyala.
   - Dikelilingi lautan dengan jembatan merah ikonis lengkap dengan mobil yang melintas.
   - Memiliki 4 pulau landmark (Rumah Sakit, Kantor Polisi, Sekolah, dan Taman) yang dikelilingi bangunan kecil acak.

2. Village (Pedesaan)
   - Suasana pedesaan yang tenang dan asri dengan pencahayaan matahari senja yang hangat (golden hour).
   - Tiga titik utama penanda QR (Finder Patterns) diubah menjadi bangunan lumbung (Barn) klasik berwarna merah pekat, biru, atau marun.
   - Lingkungan dikelilingi rumput hijau, pepohonan pinus, dan pegunungan salju yang mengambang di atas sungai biru pekat.

3. Cyberpunk (Sci-Fi Neon Abyss)
   - Kota masa depan bergaya dystopian yang dikelilingi jurang kelam hitam.
   - Menggunakan warna bangunan yang sangat gelap (pitch black) yang kontras dengan lantai sirkuit hologram neon pucat.
   - Penuh ornamen sci-fi seperti mobil terbang (hovercars), kabut gelap di bawah jurang, dan lampu neon di sekeliling batas fondasi kota.

---

## Cara Penggunaan

1. Buka file index.html menggunakan browser web modern apa pun (Chrome, Edge, Firefox, Safari). Tidak memerlukan server (zero setup).
2. Di panel kiri atas, masukkan teks atau URL yang Anda inginkan pada kolom input (atau klik tombol preset seperti Google/GitHub).
3. Klik tombol Generate untuk memuat kota 3D Anda.
4. Pilih Tema dari menu dropdown untuk mengubah gaya visual.
5. Klik Acak untuk merotasi palet warna dan merombak variasi bangunan secara acak.
6. Navigasi 3D:
   - Klik Kiri + Geser: Memutar (rotasi) kamera.
   - Scroll Mouse: Zoom in / Zoom out.
   - Klik Kanan + Geser: Menggeser (pan) posisi kamera.
7. Di pojok kanan bawah, klik Ikon QR Code untuk masuk ke mode pemindaian (Tampak Atas).
8. Klik tombol Download berwarna hijau untuk langsung menyimpan hasil scan QR dalam format gambar .png.

---

## Teknologi yang Digunakan

Aplikasi ini berjalan murni di sisi client (Browser) tanpa backend, dibangun menggunakan:
- HTML5 & CSS3 (Animasi Glassmorphism UI)
- Three.js (Rendering 3D, Material, Pencahayaan, dan Post-Processing UnrealBloom)
- GSAP (Animasi transisi kamera yang smooth)
- qrcode-generator (Mesin pembuat matriks/pola 2D QR Code)

---

Dibuat untuk memberikan pengalaman QR Code terbaik!
