# RIZE PORTFOLIO

Personal portfolio website untuk menampilkan karya, kemampuan, pengalaman, dan pencapaian.

## 🎨 Preview

Website ini memiliki desain minimalis modern dengan tema dark charcoal dan aksen biru elektrik.

## 🚀 Cara Menjalankan

### Lokal
1. Clone atau download repository ini
2. Buka file `index.html` di browser

### GitHub Pages
1. Upload semua file ke repository GitHub
2. Buka **Settings → Pages**
3. Pilih branch `main` dan folder `/ (root)`
4. Website akan live di `https://username.github.io/nama-repo`

## 📁 Struktur File

```
├── index.html      # Struktur HTML utama
├── style.css       # Styling dan layout
├── script.js       # Interaksi (filter, mobile menu, animasi)
├── README.md       # Dokumentasi
└── assets/         # Folder untuk gambar karya
```

## ✏️ Cara Mengedit

### Mengganti Gambar Karya
1. Simpan gambar di folder `assets/`
2. Buka `index.html`
3. Cari bagian `<!-- Project X -->`
4. Ganti:
```html
<div class="placeholder-img">
    <svg>...</svg>
</div>
```
dengan:
```html
<img src="assets/nama-gambar.jpg" alt="Nama Proyek">
```

### Mengganti Link Kontak
Buka `index.html`, cari bagian `<!-- CONTACT SECTION -->`, lalu edit `href` pada setiap `contact-item`:
- Email: `mailto:email@example.com`
- YouTube: `https://youtube.com/@username`
- GitHub: `https://github.com/username`
- Instagram: `https://instagram.com/username`

### Menambah/Menghapus Proyek
Duplikasi atau hapus blok `<article class="project-card">` di bagian Works. Sesuaikan:
- `data-category` → kategori (animation, 3d, video, it)
- `project-image` → thumbnail
- `project-info` → judul, deskripsi, link

### Mengubah Warna Aksen
Buka `style.css`, edit variabel di `:root`:
```css
--accent: #3b82f6;        /* Biru elektrik */
--accent-hover: #60a5fa;  /* Biru lebih terang */
```

## 🛠️ Teknologi

- HTML5
- CSS3 (Custom Properties, Grid, Flexbox)
- Vanilla JavaScript
- Google Fonts (Inter)

## 📱 Fitur

- ✅ Responsive (Mobile, Tablet, Desktop)
- ✅ Filter kategori proyek
- ✅ Smooth scroll navigation
- ✅ Mobile menu hamburger
- ✅ Fade-in animation on scroll
- ✅ Dark theme
- ✅ Siap deploy ke GitHub Pages

## 📄 Lisensi

© 2026 Rize Animation. All rights reserved.