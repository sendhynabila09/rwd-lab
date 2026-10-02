# Praktikum Rekayasa Antarmuka Web

Project ini dibuat untuk tugas Praktik Rekayasa Antarmuka Web. Project menggunakan HTML5 dan CSS3 tanpa framework CSS eksternal.

## Struktur Folder

```text
rwd-lab/
├── index.html
├── css/
│   ├── reset.css
│   ├── variables.css
│   └── style.css
├── assets/
│   └── images/
├── docs/
│   └── screenshots/
├── README.md
├── .gitignore
└── Laporan
```

## Materi yang Dikerjakan

Beberapa materi yang diterapkan pada project ini:

- Semantic HTML5
- Accessibility Tree dan skip-link
- Box Model dan `box-sizing`
- CSS variables untuk token desain
- Flexbox untuk navigasi
- CSS Grid untuk katalog kartu
- Responsive design dan media query
- Pengujian pada beberapa ukuran layar
- Keyboard navigation dan audit accessibility

## Cara Menjalankan

1. Buka folder `rwd-lab` di VS Code.
2. Jalankan `index.html` menggunakan Live Server.
3. Buka halaman pada browser.
4. Gunakan DevTools untuk melihat struktur HTML, Box Model, Flexbox, Grid, dan Accessibility.

## Pengujian

Pengujian dilakukan dengan melihat perubahan tampilan pada beberapa ukuran viewport. Ukuran yang digunakan mengikuti modul, yaitu 375px, 768px, dan 1440px. Selain itu, halaman juga dicoba pada ukuran yang lebih kecil dan lebih besar untuk melihat apakah muncul horizontal scrollbar.

Hasil pengujian dan screenshot dimasukkan ke laporan praktikum setelah pengujian dilakukan.

## Matriks Pengujian

| ID Uji | Fitur | Viewport | Yang Dicek | Hasil Aktual | Status | Bukti |
|---|---|---|---|---|---|---|
| TC-01 | Navigasi menu mobile | 360px–480px | Menu tetap terbaca dan tidak terpotong | Diisi setelah pengujian | Diisi setelah pengujian | `docs/screenshots/tc-01-nav.png` |
| TC-02 | Hero section | 768px | Layout menyesuaikan ukuran tablet | Diisi setelah pengujian | Diisi setelah pengujian | `docs/screenshots/tc-02-hero.png` |
| TC-03 | Grid katalog | 360px–1920px | Jumlah kolom menyesuaikan dan tidak ada overflow horizontal | Diisi setelah pengujian | Diisi setelah pengujian | `docs/screenshots/tc-03-grid.png` |
| TC-04 | Keyboard navigation | Tombol Tab | Skip-link muncul saat mendapat fokus | Diisi setelah pengujian | Diisi setelah pengujian | `docs/screenshots/tc-04-skip.png` |

## Catatan

Bagian hasil aktual dan status sengaja diisi setelah pengujian langsung supaya hasil pada README sesuai dengan kondisi project yang benar-benar dijalankan.
