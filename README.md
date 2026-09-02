# InstaDeck landing page

Landing page statis dan responsif untuk InstaDeck, layanan yang mengubah kata kunci atau URL artikel menjadi carousel, Story, visual, dan caption secara otomatis.

Desain menggunakan palet produk: putih, abu-abu muda, dan oranye `#FF4526`.

Logo resmi disimpan secara lokal di `assets/instadeck-logo.png` sehingga halaman tidak bergantung pada hotlink Cloudinary.

Enam logo pada section **Our Client** disimpan di `assets/clients/` dan ditampilkan dalam grid responsif tiga logo per baris.

## Menjalankan

1. Buka `index.html` langsung di browser; atau
2. Jalankan server statis dari folder ini, misalnya `python3 -m http.server 8000`, lalu buka `http://localhost:8000`.

Semua CTA utama mengarah ke:

`https://gemini.google.com/share/c0ca6ce72be3`

## Catatan

- Font Manrope dimuat dari Google Fonts. Jika halaman harus sepenuhnya offline, hapus baris `@import` di CSS; fallback sistem sudah disiapkan.
- Tidak ada framework, build step, atau dependensi JavaScript.
