# TOKO KITA – Kasir dan Stok (Versi awal)

## Isi
- `index.html`: aplikasi kasir dan stok.
- `manifest.json`: identitas aplikasi yang bisa dipasang di layar utama.
- `sw.js`: cache dasar agar aplikasi dapat dibuka offline setelah kunjungan online pertama.

## Cara memasang dari HP Android
1. Ekstrak ZIP ini di HP.
2. Buat akun / masuk ke GitHub melalui Chrome.
3. Buat repository baru, misalnya `toko-kita`.
4. Unggah ketiga file (`index.html`, `manifest.json`, `sw.js`) ke halaman utama repository.
5. Buka Settings > Pages.
6. Pada Build and deployment, pilih Deploy from a branch, branch `main`, folder `/ (root)`, lalu Save.
7. Tunggu sampai alamat GitHub Pages muncul. Buka alamat tersebut di Chrome.
8. Izinkan kamera jika diminta. Dari menu Chrome pilih Install app atau Add to Home screen.

## Catatan penting
- Gunakan HTTPS (GitHub Pages) agar izin kamera tersedia.
- Data produk/transaksi disimpan di browser HP yang digunakan (IndexedDB), bukan otomatis tersinkron ke HP lain.
- Jangan hapus data situs/browser sebelum membuat backup.
- Scan menggunakan library eksternal yang perlu dimuat saat pertama kali online. Fitur scan perlu diuji pada HP dan jenis barcode toko.
- Versi awal ini memakai pembayaran tunai, satuan bebas, dan backup JSON.
- Uji transaksi dengan barang contoh sebelum dipakai untuk penjualan sungguhan.
