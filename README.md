# Coba-file-MD

# Kalkulator Sederhana

## Deskripsi

Ini adalah sebuah aplikasi kalkulator sederhana yang memungkinkan pengguna untuk melakukan operasi perhitungan dasar. Aplikasi ini dibuat dengan menggunakan HTML, CSS, dan PHP.

## Struktur Kode

Kode aplikasi ini terdiri dari beberapa komponen utama:

### 1. Deklarasi Dokumen HTML

```html
<!DOCTYPE html>sss
<html>
  <head>
    <title>Kalkulator Sederhana</title>
  </head>
  <body></body>
</html>
```

### 2. CSS Styling

<!DOCTYPE html> digunakan untuk mendeklarasikan jenis dokumen HTML yang digunakan.
<html> adalah elemen root yang mengelilingi seluruh konten HTML.
<head> berisi informasi meta dan judul halaman.

<style>
    /* CSS Styling untuk tampilan halaman */
    /* ... */
</style>

Bagian ini berisi peraturan gaya (CSS) untuk memformat tampilan halaman web, termasuk warna latar belakang, teks, kotak, dan efek hover.

### 3. Judul Halaman

<h1>Kalkulator Sederhana</h1>

Elemen <h1> digunakan untuk menampilkan judul halaman web, dalam hal ini "Kalkulator Sederhana."

### 4. Formulir Input

<form method="post" action="">
    <fieldset>
        <!-- ... -->
    </fieldset>
    <input type="submit" name="hitung" value="Hitung" required>
</form>

Sebuah formulir yang berisi dua kolom input untuk bilangan pertama dan kedua. Elemen <fieldset> digunakan untuk mengelompokkan input dan elemen <input type="submit"> untuk mengirimkan perhitungan.

### 5. Logika Perhitungan (PHP)

<?php
if (isset($_POST['hitung'])) {
    // ... Logika perhitungan
}
?>

Bagian PHP yang dijalankan saat tombol "Hitung" ditekan. Ini mengambil input, melakukan perhitungan, dan menampilkan hasilnya dalam elemen-elemen HTML yang sesuai.

### 6. Kotak Hasil Perhitungan

<div class="result-box">
    <!-- ... Hasil perhitungan ditampilkan di sini -->
</div>

Setiap hasil perhitungan ditampilkan dalam kotak-kotakan terpisah dengan class "result-box." Kotak-kotak ini dapat dihover untuk memperbesar ukuran 10%.

### Garis Ganda

<div class="double-hr"></div>

Elemen ini digunakan untuk membuat garis ganda sebagai pemisah antara bilangan input dan hasil perhitungan.

## Cara Menggunakan Aplikasi

1. Masukkan bilangan pertama dan kedua
2. Pilih operasi perhitungan yang diinginkan
3. Tekan tombol "Hitung"
4. Hasil perhitungan akan ditampilkan di bawah kotak input
