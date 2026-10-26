# EXP Lane Academy — Website Starter

Template website edukasi EXP Lane Mobile Legends dengan desain dark tactical, aksen lime, modul materi, dan layout responsif.

## Isi paket
- `index.html` — halaman utama dan bagian materi
- `style.css` — seluruh gaya visual dan responsive layout
- `script.js` — interaksi menu mobile
- `assets/` — folder untuk gambar hero/ilustrasi yang ingin ditambahkan

## Cara melihat website di komputer
1. Ekstrak file ZIP.
2. Buka `index.html` di browser.
3. Internet diperlukan untuk memuat font Google Fonts. Website tetap bisa dibuka tanpa font tersebut.

## Publikasi gratis dengan GitHub Pages
1. Buat akun/login di https://github.com
2. Buat repository baru, misalnya `exp-lane-academy`.
3. Upload `index.html`, `style.css`, `script.js`, dan folder `assets`.
4. Buka **Settings → Pages**.
5. Pada **Build and deployment**, pilih **Deploy from a branch**, branch `main`, folder `/ (root)`, lalu Save.
6. Tunggu proses deploy dan buka URL yang ditampilkan GitHub Pages.

## Menggunakan desain ini di Google Sites
Google Sites tidak dapat mengimpor satu ZIP sebagai website utuh atau menjalankan seluruh HTML/CSS halaman secara native.
- Buat halaman di https://sites.google.com.
- Buat halaman: Beranda, Laning Phase, Pilihan Hero, Counter Hero, dan Team Fight/Rotasi.
- Gunakan tema gelap, latar navy, aksen hijau lime, dan kartu modul sebagai panduan desain.
- Untuk menampilkan versi yang di-host di GitHub Pages, gunakan **Insert → Embed → By URL** lalu masukkan URL GitHub Pages. Jika embed diblokir oleh browser/Google Sites, tampilkan tombol/link yang membuka website di tab baru.
- Untuk menyematkan bagian HTML langsung, Google Sites mendukung **Embed code** pada beberapa jenis konten, tetapi tidak untuk mengganti keseluruhan struktur situs. Kode ini paling cocok dipublikasikan melalui GitHub Pages.

## Mengganti ilustrasi dengan gambar hero Mobile Legends
Bagian cover pada template ini menggunakan ilustrasi fighter CSS buatan sendiri, bukan gambar hero resmi. Untuk memakai gambar hero yang kamu punya izin gunakan:
1. Simpan gambar ke folder `assets/`, misalnya `exp-hero.png`.
2. Tambahkan elemen gambar di dalam `<div class="hero-art">` pada `index.html`, atau ganti ilustrasi CSS dengan gambar.
3. Pastikan hak penggunaan gambar sesuai. Untuk materi hero, cantumkan nama hero dan perbarui informasi mengikuti patch terbaru.

## Catatan materi
Teks materi adalah kerangka awal edukasi, bukan tier list patch terkini. Update rekomendasi hero, item, emblem, dan matchup secara berkala.
