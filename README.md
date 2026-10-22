# Nexora Coffee Shop

Website kedai kopi modern untuk menampilkan merek, menu, dan informasi kafe.

> **Catatan:** Repositori ini berisi hasil build aplikasi React untuk deployment. Aplikasi asli dibuat dengan React, Vite, Tailwind CSS, dan Express.js. Kode sumber asli mungkin tidak ada di sini.

## Tentang Proyek

Nexora Coffee Shop adalah website untuk kafe modern. Tujuannya sederhana: menampilkan identitas kafe, daftar menu, dan informasi penting agar mudah ditemukan pengunjung.

## Fitur

- Halaman utama yang menampilkan identitas kafe
- Daftar menu minuman dan makanan
- Informasi kafe dan kontak
- Tampilan responsif untuk HP, tablet, dan desktop
- Navigasi yang mudah digunakan

> Fitur pemesanan atau pembayaran memerlukan backend dan tidak termasuk dalam build statis ini.

## Teknologi

- **React** - untuk antarmuka
- **Vite** - untuk build
- **Tailwind CSS** - untuk styling
- **Express.js** - untuk backend (rencana)

## Cara Menjalankan

Jika ada folder `dist/`:

```bash
npx serve dist
```

Jika kode sumber tersedia:

```bash
npm install
npm run build
npm run preview
```

## Deployment

Bisa di-deploy di Vercel, Netlify, atau hosting statis lainnya. Jika menggunakan React Router, atur agar semua rute diarahkan ke `index.html`.

## Rencana Pengembangan

- Menghubungkan menu ke database
- Menambahkan fitur kontak dan reservasi
- Meningkatkan SEO dan aksesibilitas

## Kredit

Dibuat sebagai proyek portofolio oleh Ko San San.
