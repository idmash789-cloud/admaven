# admaven — Halaman Konfirmasi

Halaman konfirmasi satu file (`index.html`), tanpa build step.

## Cara kerja

Pop-up di tengah layar menampilkan status "Koneksi Aman", dengan dua tombol:

- **Lanjut** → https://www.fb.com
- **Tutup** (dan tombol `×` di pojok pop-up) → https://www.home.com

Tombol memakai link biasa (`<a href>`), jadi tetap berfungsi walau JavaScript nonaktif. Tidak ada redirect otomatis — perpindahan hanya terjadi saat tombol diklik.

## Menjalankan / deploy

- Lokal: buka `index.html` di browser.
- GitHub Pages: Settings → Pages → Deploy from a branch → `main` / root, lalu buka URL Pages repo ini.
- Cloudflare Pages: hubungkan repo ini, build command kosong, output directory root.

Catatan: halaman ini adalah pop-up konfirmasi generik buatan sendiri, bukan halaman resmi Cloudflare.
