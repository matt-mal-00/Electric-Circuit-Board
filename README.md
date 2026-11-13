# Papan Sirkuit Virtual

Simulator rangkaian listrik di browser (tanpa server dan tanpa library luar).

## Cara menayangkan lewat GitHub Pages
1. Buat repository baru di GitHub (misalnya `papan-sirkuit`).
2. Unggah semua isi folder ini (`index.html`, `manifest.webmanifest`, `sw.js`, folder `icons`) ke cabang `main`.
3. Buka **Settings > Pages**, pada *Build and deployment* pilih **Deploy from a branch**, cabang `main`, folder `/ (root)`, lalu Save.
4. Tunggu 1 sampai 2 menit. Alamatnya: `https://NAMA-GITHUB-KAMU.github.io/papan-sirkuit/`

## Memasang ikon di perangkat
- **Laptop (Chrome atau Edge)**: buka alamat di atas, klik ikon pasang (monitor dengan panah) di ujung kanan kolom alamat, lalu **Install**. Ikon muncul di desktop atau menu Start.
- **Tablet atau HP Android (Chrome)**: menu titik tiga, lalu **Instal aplikasi** atau **Tambahkan ke layar utama**.
- **iPad atau iPhone (Safari)**: tombol Bagikan, lalu **Tambahkan ke Layar Utama**.

Setelah dibuka sekali, aplikasi bisa dipakai tanpa internet. Setelah mengunggah versi baru, ubah `V` di `sw.js` (misalnya `sirkuit-v2`) agar perangkat memuat versi terbaru.
