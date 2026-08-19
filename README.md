# Website Srilex Buditra — V4

Paket website lengkap berdasarkan desain gambar nomor 1.

Isi: index.html, style.css, script.js, assets/profile.jpg, dan assets/design-reference.png.
Website responsive dan siap diunggah ke GitHub Pages.

# Website Srilex Buditra — Full Stack Developer

Website portfolio + formulir estimasi harga yang dibuat mengikuti desain dark navy + gold pada mockup pilihan.

## Fitur
- Responsive desktop, tablet, dan mobile
- Foto close-up di dalam lingkaran hero
- Menu navigasi dan mobile menu
- Layanan dan portfolio
- Paket harga Starter, Professional, Business, Custom
- Formulir estimasi harga otomatis
- Tombol Kirim ke WhatsApp
- Tombol **Cetak / Simpan PDF** memakai dialog print browser (pilih **Save as PDF**)
- FAQ accordion
- Print CSS agar hasil PDF lebih bersih
- Tanpa framework atau CDN, sehingga cocok untuk GitHub Pages

## Cara menjalankan
1. Buka `index.html` di browser untuk tes lokal.
2. Untuk GitHub Pages, upload seluruh isi folder ini ke repository `srilexbuditra.github.io`.
3. Pastikan `index.html` berada di root repository.
4. Buka Settings → Pages → Deploy from branch → `main` → `/ (root)`.

## WAJIB: ganti nomor WhatsApp
Buka `script.js`, cari:

```js
const WHATSAPP_NUMBER = "6282135238350";
```

Ganti dengan nomor WhatsApp Anda dalam format internasional tanpa tanda `+`, spasi, atau `-`.

Contoh: `6282135238350`

## Foto
Foto Anda berada di `assets/profile.jpg`. Jika ingin mengganti foto, gunakan nama file yang sama agar HTML tidak perlu diubah.
