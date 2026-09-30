# ChannaGrow Buku — PWA

Versi ini mempertahankan aplikasi HTML lokal dan menambahkan kemampuan Progressive Web App (PWA).

## File untuk GitHub Pages
- `index.html` — aplikasi utama
- `manifest.json` — identitas/install PWA
- `sw.js` — service worker/offline cache
- `icon-192.png` dan `icon-512.png` — ikon aplikasi

## Cara memasang di Chrome
1. Upload semua file di atas ke repository GitHub, dengan `index.html` di folder yang sama dengan `manifest.json` dan `sw.js`.
2. Aktifkan GitHub Pages dari branch/folder tersebut.
3. Buka alamat HTTPS GitHub Pages, misalnya `https://username.github.io/nama-repo/`.
4. Tunggu aplikasi selesai dimuat sekali. Chrome kemudian dapat menampilkan opsi **Install ChannaGrow Buku** di address bar/menu Chrome.
5. Tombol **Install ChannaGrow Buku** di dalam aplikasi juga akan muncul ketika Chrome menyediakan install prompt.

## Catatan data
Data pembukuan tetap disimpan di `localStorage` browser seperti versi offline. PWA tidak otomatis memindahkan data ke server. Gunakan Backup JSON secara berkala.
