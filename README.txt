WEDNESS AI VECTOR
=================

Versi awal aplikasi trace vector berbasis web responsif yang dapat dipasang di Android sebagai PWA.

FITUR
- Upload JPG, PNG, WEBP
- Mode Hitam Putih, Full Color, Line Art
- Pengaturan jumlah warna, noise, smoothing, threshold, invert
- Opsi menghapus bidang putih agar hasil SVG berlatar transparan
- Download SVG, PNG, PDF
- Pemrosesan gambar di browser (tidak dikirim ke server)

CARA MENJALANKAN
1. Ekstrak ZIP.
2. Upload folder ini ke hosting HTTPS (misalnya GitHub Pages atau Netlify).
3. Buka URL hosting melalui Chrome Android.
4. Pilih menu Chrome > Install app / Tambahkan ke layar utama.

CATATAN
- Untuk instalasi PWA diperlukan hosting HTTPS atau localhost.
- Trace menggunakan ImageTracerJS dari jsDelivr CDN dan ekspor PDF menggunakan jsPDF CDN, sehingga koneksi internet diperlukan untuk memuat library.
- Versi ini adalah aplikasi web installable (PWA), bukan APK native. APK dapat dibuat kemudian dengan membungkus PWA/web app menggunakan Android Trusted Web Activity atau Capacitor.
- SVG adalah vector hasil tracing otomatis; detail foto yang kompleks mungkin perlu dirapikan lagi di Inkscape/CorelDRAW.
