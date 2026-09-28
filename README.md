# Praktikum 2 — HTML Lanjutan

## 📌 Deskripsi

Repository ini berisi hasil Praktikum 2 Pemrograman Web dengan materi **HTML Lanjutan**.

Pada praktikum ini dipelajari beberapa materi HTML, yaitu:

* Tabel HTML
* Struktur tabel menggunakan `thead`, `tbody`, dan `tfoot`
* Form HTML
* Berbagai jenis input
* Radio button dan checkbox
* Select dan textarea
* Validasi form dasar
* Semantic HTML
* Multimedia berupa audio dan video
* Proyek mini biodata mahasiswa

## 🎯 Tujuan Praktikum

Tujuan dari praktikum ini adalah:

1. Memahami penggunaan tabel pada HTML.
2. Memahami penggunaan form dan berbagai jenis input HTML.
3. Menerapkan semantic HTML untuk menyusun struktur halaman.
4. Menambahkan elemen multimedia pada halaman web.
5. Menerapkan validasi form dasar menggunakan atribut HTML.

## 📂 Struktur Repository

```text
Lab2Web/
│
├── index.html
├── biodata.html
│
├── media/
│   ├── audio.mp3
│   └── video.mp4
│
└── README.md
```

## 📝 Langkah-Langkah Praktikum

### 1. Membuat Tabel Data Mahasiswa

Pada langkah pertama dibuat tabel yang berisi data mahasiswa seperti:

* NIM
* Nama
* Program Studi

Tabel dibuat menggunakan elemen:

```html
<table>
<tr>
<th>
<td>
```

### 2. Mengembangkan Struktur Tabel

Tabel dikembangkan menggunakan:

* `<caption>`
* `<thead>`
* `<tbody>`
* `<tfoot>`
* `colspan`

Contohnya digunakan untuk menampilkan data nilai praktikum dan rata-rata nilai.

### 3. Membuat Form Registrasi Mahasiswa

Form digunakan untuk menerima data dari pengguna.

Input yang digunakan antara lain:

```html
<input type="text">
<input type="email">
<input type="password">
<input type="date">
```

Form juga dilengkapi dengan tombol:

```html
<button type="submit">Daftar</button>
<button type="reset">Reset</button>
```

### 4. Radio Button dan Checkbox

Radio button digunakan untuk memilih salah satu pilihan, sedangkan checkbox dapat digunakan untuk memilih satu atau beberapa pilihan.

Contoh yang digunakan pada praktikum:

* Jenis kelamin
* Keahlian HTML
* Keahlian CSS
* Keahlian JavaScript

### 5. Select dan Textarea

Elemen `<select>` digunakan untuk membuat pilihan Program Studi.

Sedangkan `<textarea>` digunakan untuk memasukkan data alamat.

Contoh:

```html
<select id="prodi" name="prodi">
    <option value="">-- Pilih Prodi --</option>
    <option value="ti">Teknik Informatika</option>
    <option value="si">Sistem Informasi</option>
</select>

<textarea id="alamat" name="alamat"></textarea>
```

### 6. Validasi Form Dasar

Validasi dasar diterapkan menggunakan beberapa atribut HTML seperti:

* `required`
* `minlength`
* `min`
* `max`
* `type`

Contoh:

```html
<input type="text" required minlength="3">

<input type="email" required>

<input type="number" min="17" max="60" required>
```

Validasi tersebut membantu memastikan data yang dimasukkan sesuai dengan ketentuan yang diberikan.

### 7. Membuat Semantic HTML

Pada praktikum digunakan beberapa elemen semantic HTML:

```html
<header>
<nav>
<main>
<section>
<article>
<aside>
<footer>
```

Elemen tersebut digunakan untuk membuat struktur halaman menjadi lebih jelas dan terorganisasi.

### 8. Menambahkan Multimedia

Pada praktikum ditambahkan elemen multimedia berupa audio dan video.

Audio:

```html
<audio controls>
    <source src="media/audio.mp3" type="audio/mpeg">
</audio>
```

Video:

```html
<video controls width="480">
    <source src="media/video.mp4" type="video/mp4">
</video>
```

File multimedia ditempatkan di dalam folder `media`.

### 9. Proyek Mini — Biodata Mahasiswa

Pada proyek mini seluruh materi utama HTML Lanjutan digabungkan menjadi sebuah halaman **Biodata Mahasiswa**.

Halaman tersebut terdiri dari:

* Header
* Navigasi
* Data mahasiswa dalam bentuk tabel
* Form biodata
* Input nama
* Input email
* Pilihan program studi
* Alamat
* Tombol simpan
* Tombol reset
* Footer

## 🛠️ Tools yang Digunakan

* Visual Studio Code
* Web Browser
* HTML5
* GitHub

## ▶️ Cara Menjalankan

1. Download atau clone repository ini.
2. Buka folder `Lab2Web` menggunakan Visual Studio Code.
3. Buka file `index.html`.
4. Jalankan file menggunakan web browser.
5. Untuk melihat proyek biodata, buka file `biodata.html`.
6. Pastikan file audio dan video berada di dalam folder `media`.

## 📸 Dokumentasi

Screenshot hasil praktikum dapat ditambahkan pada repository sebagai dokumentasi setiap tahap pengerjaan.

## 📚 Materi yang Dipelajari

Praktikum ini mencakup:

* HTML Table
* HTML Form
* Input HTML
* Radio Button
* Checkbox
* Select
* Textarea
* Form Validation
* Semantic HTML
* Audio
* Video
* Proyek Mini Biodata Mahasiswa

## 👩‍💻 Identitas Mahasiswa

**Nama:** Nazwa Salsabila
**NIM:** 312510155
**Mata Kuliah:** Pemrograman Web
**Praktikum:** Praktikum 2 — HTML Lanjutan

## ✅ Kesimpulan

Praktikum 2 memberikan pemahaman mengenai penggunaan HTML lanjutan untuk membuat halaman web yang lebih terstruktur dan interaktif. Materi yang dipraktikkan meliputi pembuatan tabel, form, validasi input, semantic HTML, multimedia, serta penggabungan materi tersebut dalam proyek mini biodata mahasiswa.
