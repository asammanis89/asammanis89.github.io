# Katalog Template Website UMKM

15 contoh website company profile (Konter HP, Rental Mobil, Kuliner & Kafe), 5 gaya desain per kategori, lengkap dengan pratinjau desktop dan HP.

## Cara pasang di GitHub Pages
1. Buat repo baru (misal `template-website`) lalu upload seluruh isi folder ini.
2. Settings > Pages > Source: `Deploy from a branch`, branch `main`, folder `/ (root)`.
3. Situs aktif di `https://<username>.github.io/template-website/`.

## Ganti nomor WhatsApp
Edit `assets/config.js`, ubah `whatsapp` ke nomor Anda (format 62..., tanpa + dan spasi).

## Struktur
- `index.html` halaman katalog
- `viewer.html#<slug>` halaman demo dengan tombol Desktop / Tablet / HP
- `templates/<slug>/index.html` 15 template, HTML + CSS murni tanpa framework
- `shots/` gambar pratinjau, `assets/fonts/` font self-hosted (lisensi OFL)
