# Kapan Terakhir? (prototype PWA)

Isi folder:
- index.html: aplikasi (HTML, CSS, JS dalam satu file)
- manifest.webmanifest: info aplikasi untuk dipasang di layar utama
- sw.js: service worker agar bisa dibuka tanpa internet
- icon-*.png, apple-touch-icon.png: ikon

Cara mencoba di komputer:
  npx serve .
lalu buka http://localhost:3000

Agar bisa dipasang di HP, unggah folder ini ke hosting HTTPS
(misalnya Netlify Drop, Vercel, GitHub Pages, atau Cloudflare Pages).
Android/Chrome: muncul tombol "Pasang aplikasi". iPhone/Safari: Bagikan, lalu Tambah ke Layar Utama.

Data tersimpan di localStorage perangkat masing-masing.
