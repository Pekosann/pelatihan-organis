# Pelatihan Organis Kaiyuan

Situs materi **Pelatihan Organis Gereja Katolik** untuk mahasiswa Indonesia di KaiYuan Church (開元教堂), Tainan, Taiwan.

🌐 **Live site:** https://Pekosann.github.io/pelatihan-organis

## Tentang

Pelatihan 8 bulan (32 pertemuan) untuk belajar memainkan organ gereja dan mengiringi Misa Kudus. Materi mencakup:

- Notasi angka & notasi balok (數字譜 vs 五線譜)
- Teknik dasar keyboard
- Tangga nada, akor, kadens
- Pola iringan & walking bass
- Lagu-lagu liturgi (Puji Syukur, Madah Bakti, Ordinarium)
- Praktik iringan misa lengkap

## Struktur Repository

```
.
├── _config.yml              # Konfigurasi situs
├── _posts/                  # Materi mingguan (markdown)
├── _tabs/                   # Halaman tetap (silabus, pendaftaran, dll.)
├── assets/
│   ├── css/                 # Custom CSS (termasuk font Parnumation4)
│   ├── fonts/               # File font kustom
│   └── img/                 # Gambar
└── .github/workflows/       # GitHub Actions untuk auto-deploy
```

## Cara Menulis Materi Mingguan

1. Buat file baru di `_posts/` dengan format: `YYYY-MM-DD-judul-singkat.md`
2. Tambahkan front matter (lihat contoh di `_posts/2026-04-13-minggu-01-perkenalan-keyboard.md`)
3. Tulis konten dalam markdown
4. Untuk notasi angka, gunakan: `<div class="notasi-angka">...</div>`
5. Commit dan push ke branch `main` — GitHub Actions akan otomatis build & deploy

## Tema

Dibangun dengan [**Chirpy**](https://github.com/cotes2020/jekyll-theme-chirpy) Jekyll theme oleh Cotes Chung.

## Lisensi

MIT — lihat file [LICENSE](LICENSE).
