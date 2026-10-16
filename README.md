# ItsHost Store
Semua file website ada langsung di root: `index.html`, `style.css`, `app.js`, `vercel.json`, `package.json`.

## Deploy Vercel
Import repository GitHub ke Vercel, pilih Framework Preset **Other**, biarkan Build Command kosong, Output Directory `.` lalu deploy.

## Catatan penting
Login demo admin: username `itss`, password `22OKTOBER2011`. Ini hanya demo front-end: password bisa dilihat dari source JS, jadi jangan gunakan untuk melindungi admin publik. Login Google perlu Firebase Authentication dan belum aktif di template ini. Data produk/pengaturan disimpan di localStorage browser, bukan database bersama. QRIS hanya ditampilkan sebagai gambar dan tidak memverifikasi pembayaran otomatis. Pakai backend dan autentikasi sungguhan untuk produksi.
