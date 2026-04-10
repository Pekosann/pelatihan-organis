## Fonts Folder

Letakkan file font kustom di folder ini.

### Parnumation4

File yang dibutuhkan:
- `Parnumation4.woff2` (utama, paling kecil dan cepat)
- `Parnumation4.woff` (cadangan untuk browser lama, opsional)

### Cara konversi TTF/OTF ke WOFF2

1. Buka https://transfonter.org/
2. Upload `Parnumation4.ttf` (atau `.otf`)
3. Pilih format: **WOFF2** (centang juga **WOFF** jika ingin dukungan browser lama)
4. (Opsional) Centang **Subset** dan masukkan karakter yang dipakai notasi angka, misal:
   `0123456789.,-/|()_<>+=#♭♯`
5. Klik **Convert**, download file
6. Salin file `.woff2` ke folder ini

### Penggunaan dalam post

```html
<div class="notasi-angka">
1 2 3 4 | 5 . 3 1 | 2 . . . |
</div>
```

Definisi font ada di `assets/css/jekyll-theme-chirpy.scss`.
