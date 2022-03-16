# Praktikum 1: Dasar HTML
```
Maulana Hasanudin
312010106
TI.20.D1
```
## Langkah 1
### Buka VSCode dan buat file HTML baru. Setelah itu buat struktur dasar HTML
```
<!DOCTYPE html>
<html>
<head>
    <title>Tag HTML Dasar</title>
</head>
<body>

</body>
</html>
```
<img width="1070" alt="1" src="https://user-images.githubusercontent.com/101716660/158663582-6aeb62c5-3333-461f-a3fc-ee6dca806e15.png">
## LANGKAH 2
### Membuat 2 buah paragraf dan atur atribut paragraf (Rata Kiri / Rata Kanan / Rata Tengah / Sama Rata)
```
<!-- Ini adalah paragraf pertama -->
<p align="center">Kami sedang belajar \HTML dasar, pada matakuliah Pemrograman
    Web di Prodi Teknik Informatika Universitas Pelita Bangsa. Pelajaran pertama
    yang kami dapat adalah membuat tampilan web sederhana dalam rangka mengenal
    tag-tag dasar HTML.</p>

<!-- Ini adalah paragraf kedua -->
<p align="right">Ini merupakan sebuah paragraf yang terdiri dari beberapa
    kalimat yang saling mendukung sehingga menjadi satu kesatuan. Paragraf dibuat
    dengan menggunakan tag dasar html.</p>
```
<img width="1070" alt="2" src="https://user-images.githubusercontent.com/101716660/158663606-3cfd6111-2cb5-40a5-8135-6aa2b7acc360.png">
## LANGKAH 3
### penambahan judul menggunakan Tag Heading (h1, h2, h3, h4, h5, h6). Semakin besar angka Tag Heading, Semakin kecil ukuran Headingnya.
```
<!-- judul paragraf pertama -->
<h1>Belajar Dasar HTML</h1>

<!-- judul paragraf kedua -->
<h2>Paragraf pada HTML</h2>
```
<img width="1070" alt="3" src="https://user-images.githubusercontent.com/101716660/158663638-7bfc830b-0d39-44e4-af43-508d827b764c.png">
## LANGKAH 4
### Memformat Teks menggunakan format-format teks yang ada seperti <b>, <strong>, <i>, <em>, <mark>, <small>, <dell>, <ins>, <sub>, dan <sup>.
```
<p align="left">Kami sedang belajar <mark>HTML dasar</mark>, pada matakuliah <b>Pemrograman
    Web</b> di Prodi <i>Teknik Informatika</i> <ins>Universitas Pelita Bangsa</ins>. Pelajaran pertama
    yang kami dapat adalah membuat tampilan web sederhana dalam rangka mengenal
    tag-tag dasar HTML.</p>
```
<img width="1070" alt="4" src="https://user-images.githubusercontent.com/101716660/158663660-823de52d-3da9-4d18-afa0-4dc66abfebdd.png">
## LANGKAH 5
### Menyisipkan Gambar dan mengatur ukuran gambar. Sebelum menyisipkan gambar, file HTML yg sudah dibuat dijadikan satu dengan gambar yg akan disisipkan.
<img width="1070" alt="5" src="https://user-images.githubusercontent.com/101716660/158663739-1e27dd6c-abe3-4048-bdfd-14786cac7fa0.png">
```
<!-- sub judul paragraf -->
<h3>Menambahkan Gambar</h3>
<!-- menambahkan gambar pada dokumen -->
<img src="Logo_UPB.png" width="200" title="Logo Univeritas Pelita Bangsa">
```
<img width="1070" alt="6" src="https://user-images.githubusercontent.com/101716660/158663787-6f545500-f6af-4f1c-aa35-bd65aa81d8ae.png">
## LANGKAH 6
### menambahkan Hyperlink. Tambahkan hyperlink pada dokumen sebelum heading 1.
```
<!-- menambahkan link navigasi -->
<nav>
    <a href="lab1_tag_dasar.html">Dasar HTML</a>
    <a href="lab1_halaman2.html">Halaman 2</a>
    <a href="http://www.google.com">Halaman Web Eksternal Google</a>
    </nav>
    <hr>
```
<img width="1070" alt="7" src="https://user-images.githubusercontent.com/101716660/158663821-758fea21-d57f-4c31-9f73-fbae16ac3cf6.png">
## LANGKAH 7
### Membuat halaman ke 2 yang akan terhubung dengan halaman pertama menggunakan Hyperlink.
```
<!DOCTYPE html>
<html>
<head>
    <title>Tag HTML Dasar</title>
</head>
<body>

<h1>Halaman Ke 2</h1>

<p align="justify">Kami sedang belajar.</p>

</body>
</html>
```
<img width="1070" alt="8" src="https://user-images.githubusercontent.com/101716660/158663898-ef95b6cc-6753-4e60-ac4c-ec2ad9f32729.png">
## Jawab Pertanyaan Berikut
### 1.lakukan perubahan pada kode sesuai dengan keinginan anda, amati perubahannya adakah kesalahan ketika terjadi kesalahan penulisan tag?
```
Ada error ketika saya salah penulisan Heading <h1> tidak ditutup dengan </h1> jadi tidak terjadi perubahan.
```
### 2.Apa perbedaan dari tag <p>dengan tag <br>berikan penjelasannya!
```
Dari hasil praktek saya sendiri, perbedaan  tag <br> jarak enter nya lebih jauh 1 line dibandingkan
dengan tag <p> yg jarak enter nya tidak terlalu jauh.
```
### 3.Apa perbedaan atribut title dan alt pada tag <img>, berikan penjelasannya!
```
atribut tittle pada tag <img> digunakan untuk memberi judul pada gambar yg disisipkan, sedangkan
atribut alt pada tag <img> digunakan untuk memberi deskripsi pada gambar yg disisipkan
```
### 4.Untuk mengatur ukuran gambar, digunakan atribut width dan height. Agar tampilan proporsional sebaiknya kedua atribut tersebut diisi semua atau tidak? Berikan penjelasannya!
```
Untuk mempertahankan proporsi gambar, namun tetap membuat gambar menjadi besar/kecil, cantumkan
hanya salah satu atribut saja (width saja atau height saja, namun tidak keduanya). Misalkan
jika kita menetapkan atribut width=200px (tanpa mencantumkan height), maka web browser akan
menampilkan gambar dengan lebar 200px, dan menghitung secara otomatis tinggi gambar agar gambar
tetap proporsional.
```
### 5.Pada link tambahkan atribut target dengan nilai atribut yang bervariasi (_blank, _self, _top, _parent), apa yang pada masing-masing nilai atribut tersebut?
```
Nilai _blank akan membuka link/halaman di tab baru.
Nilai _self akan membuka link/halaman di tab saat ini.
Nilai _top membuka link/halaman dan membatalkan semua frame.
Nilai _parent membuka link/halaman pada parent frame.
```
