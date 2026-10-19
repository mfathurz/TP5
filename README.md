# TP Modul 5 - Bootstrap

## 1. Pengertian Bootstrap

Bootstrap adalah framework CSS yang digunakan untuk mempermudah pembuatan tampilan website. Bootstrap menyediakan class siap pakai untuk mengatur tampilan seperti tombol, form, navbar, dan tata letak. Bootstrap juga membantu membuat website agar bisa menyesuaikan ukuran layar perangkat

## 2. Memasang Bootstrap

Bootstrap dapat digunakan dengan beberapa cara, yaitu:

1. Menggunakan CDN dengan menambahkan link Bootstrap ke file HTML
2. Mengunduh file Bootstrap, kemudian menghubungkannya ke file HTML
3. Menggunakan package manager seperti npm untuk memasang Bootstrap pada proyek

Pada praktikum ini, Bootstrap digunakan melalui CDN versi 5.3.8

## 3. Grid dan Breakpoint

Grid adalah sistem Bootstrap untuk membagi halaman menjadi baris dan kolom agar tata letak website lebih rapi

Breakpoint digunakan untuk menyesuaikan tampilan website berdasarkan ukuran layar. Contohnya, `sm`, `md`, `lg`, `xl`, dan `xxl`, yang memiliki batas ukuran layar berbeda

Contoh class grid:

```html
<div class="col-12 col-md-6">
    Konten website
</div>
```

Class `col-12` membuat konten memenuhi lebar baris, sedangkan `col-md-6` membuat konten menggunakan setengah lebar baris pada layar berukuran medium atau lebih besar

## 4. Class Bootstrap
Berikut lima contoh class Bootstrap beserta kegunaannya:
  1. container untuk mengatur area konten website
  2. text-center untuk membuat teks berada di tengah
  3. btn untuk memberikan tampilan tombol
  4. mt-3 untuk memberikan jarak di bagian atas elemen
  5. img-fluid untuk membuat gambar menyesuaikan lebar wadahnya

## 5. Gambar Responsif

Untuk membuat gambar responsif, kita dapat menggunakan class `img-fluid` pada elemen gambar. Class ini membuat gambar menyesuaikan lebar wadahnya dan tinggi gambar menyesuaikan secara otomatis, sehingga gambar tetap proporsional pada berbagai ukuran layar

Contoh:

```html
<img src="gambar.jpg" class="img-fluid" alt="Contoh gambar">
```
