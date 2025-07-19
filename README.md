# 📦 icodex-ui-fonts

`icodex-ui-fonts` adalah kumpulan ikon yang dikemas sebagai webfont, dibuat menggunakan [Fontello](https://fontello.com). Webfont ini ringan, mudah digunakan, dan kompatibel dengan semua browser modern. Cocok untuk UI aplikasi, panel admin, atau editor berbasis web.

---

## 📁 Struktur Folder
```txt
├── css/
│ ├── fontello.css
│ ├── fontello-embedded.css
│ └── animation.css
├── font/
│ ├── icodex-ui-fonts.woff
│ ├── icodex-ui-fonts.ttf
│ ├── icodex-ui-fonts.svg
│ └── icodex-ui-fonts.eot
├── config.json
├── demo.html
└── README.md
```

---

## 🚀 Cara Menggunakan

### 1. Tambahkan file CSS ke dalam `<head>`

```html
<link rel="stylesheet" href="css/icodex-ui-fonts.css">

<i class="icon-icodex-folder"></i>

```
---

🎨 Daftar Ikon Tersedia
Berikut adalah ikon-ikon yang tersedia di font ini:

```txt
icon-icodex-file-plus-2   → 0xe800
icon-icodex-inbox         → 0xe801
icon-icodex-search-code   → 0xe802
icon-icodex-folder-2      → 0xe803
icon-icodex-git-branch    → 0xe804
icon-icodex-folder        → 0xe805
icon-icodex-home-2        → 0xe806
```
Lihat juga tampilan visualnya di file demo.html.

💡 Contoh Penggunaan Lengkap
```html
<!DOCTYPE html>
<html>
  <head>
    <meta charset="UTF-8" />
    <title>Contoh Icon</title>
    <link rel="stylesheet" href="css/fontello.css" />
  </head>
  <body>
    <i class="icon-icodex-folder"></i> Folder
    <i class="icon-icodex-search-code"></i> Cari
  </body>
</html>
```

⚙️ Cara Modifikasi Ikon
Untuk menambahkan atau mengganti ikon:

Buka: https://fontello.com

Klik tombol Import config.json

Tambahkan ikon, ubah nama class jika perlu

Klik Download webfont

Gantikan isi folder /css, /font, dan config.json dengan versi baru

📄 Lisensi
File ini dibuat menggunakan Fontello.

Karena file LICENSE.txt tidak disertakan, maka:

- Semua ikon berasal dari font set yang tidak memerlukan lisensi tambahan

- Font seperti Entypo, Font Awesome 4.7, Typicons biasanya berlisensi open-source

 Ikon dikompilasi menggunakan proyek open-source [Fontello](https://fontello.com)

