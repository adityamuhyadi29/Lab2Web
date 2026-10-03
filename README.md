# Lab2Web

Praktikum ini membahas dasar-dasar HTML lanjutan, meliputi pembuatan tabel, form, input, semantic HTML, multimedia, serta validasi form dasar.

## Membuat Tabel Mahasiswa

Pada langkah pertama, dibuat tabel untuk menampilkan data mahasiswa menggunakan beberapa elemen HTML:

- `<table>` digunakan untuk membuat tabel.
- `<tr>` digunakan untuk membuat baris tabel.
- `<th>` digunakan untuk membuat judul kolom.
- `<td>` digunakan untuk membuat data pada tabel.

### Result

![Gambar 1](Screenshot/ss1.png)

## Mengembangkan Tabel

Pada langkah ini, tabel dikembangkan dengan menggunakan beberapa elemen HTML:

- `<caption>` digunakan untuk memberikan judul tabel.
- `<thead>` digunakan untuk bagian kepala tabel.
- `<tbody>` digunakan untuk bagian isi tabel.
- `<tfoot>` digunakan untuk bagian kaki atau ringkasan tabel.
- `colspan` digunakan untuk menggabungkan beberapa kolom.

### Result

![Gambar 2](Screenshot/ss2.png)

## Membuat Form Registrasi

Form digunakan untuk menerima data dari pengguna.

Input yang digunakan antara lain:

- Nama lengkap.
- Email.
- Password.
- Tanggal lahir.
- Tombol Daftar.
- Tombol Reset.

### Result

![Gambar 3](Screenshot/ss3.png)

## Radio Button dan Checkbox

Radio button digunakan untuk memilih satu pilihan dari beberapa pilihan yang tersedia.

Contohnya adalah pilihan jenis kelamin:

- Laki-laki.
- Perempuan.

Checkbox digunakan untuk memilih satu atau lebih pilihan.

Contohnya adalah pilihan keahlian:

- HTML.
- CSS.
- JavaScript.

### Result

![Gambar 4](Screenshot/ss4.png)

## Select dan Textarea

Elemen `<select>` digunakan untuk membuat pilihan dalam bentuk dropdown.

Program studi yang tersedia:

- Teknik Informatika.
- Sistem Informasi.

Elemen `<textarea>` digunakan untuk menerima teks yang lebih panjang, seperti alamat.

### Result

![Gambar 5](Screenshot/ss5.png)

## Validasi Form Dasar

Validasi form dilakukan menggunakan beberapa atribut HTML, seperti:

- `required`
- `minlength`
- `min`
- `max`
- `type="email"`

Browser akan memberikan pesan validasi apabila pengguna menekan tombol Kirim tanpa memenuhi ketentuan yang telah ditentukan.

### Result

![Gambar 6](Screenshot/ss6.png)

## Membuat Halaman Semantic HTML

Pada langkah ini digunakan beberapa elemen semantic HTML:

- `<header>`
- `<nav>`
- `<main>`
- `<section>`
- `<article>`
- `<aside>`
- `<footer>`

Semantic HTML membantu memberikan struktur dan makna yang lebih jelas pada halaman web.

### Result

![Gambar 7](Screenshot/ss7.png)

## Menambahkan Multimedia

Pada praktikum ini ditambahkan elemen multimedia berupa audio dan video.

### Struktur Folder

```text
praktikum-2-html-lanjutan/
│
├── index.html
├── README.md
└── media/
    ├── audio.mp3
    └── video.mp4
```

Audio ditampilkan menggunakan elemen:

```html
<audio controls>
    <source src="media/audio.mp3" type="audio/mpeg">
</audio>
```

Video ditampilkan menggunakan elemen:

```html
<video controls width="480">
    <source src="media/video.mp4" type="video/mp4">
</video>
```

### Result

![Gambar 8](Screenshot/ss8.png)

## Proyek Mini — Biodata Mahasiswa

Pada proyek mini ini dibuat halaman biodata mahasiswa yang menggabungkan materi yang telah dipelajari.

Halaman memiliki beberapa bagian, yaitu:

- Semantic HTML.
- Tabel data mahasiswa.
- Form biodata.
- Validasi form.
- Select program studi.
- Textarea alamat.
- Multimedia.
- Navigasi halaman.

### Struktur Halaman

```html
<header>
    Judul halaman
</header>

<nav>
    Navigasi
</nav>

<main>
    <section>
        Data Mahasiswa
    </section>

    <section>
        Form Biodata
    </section>
</main>

<footer>
    Footer
</footer>
```

### Result

![Gambar 9](Screenshot/ss9.png)