# Modul Praktikum Pemrograman Web
Penulisan Eksternal CSS menggunakan tag <link> menggunakan atribut href untuk merujuk
kepada file css yang diletakkan pada <head> dokumen.
Contoh Eksternal CSS.

# Inline CSS dengan menambahkan kode CSS pada tag HTML sebagai atribut dan value. Penempatan
CSS secara inline hanya akan mempengaruhi satu bagian baris kode.
Contoh Inline CSS.

# CSS Selector
CSS Selector dapat berupa elemen HTML, selector class atau selector id. Penggunaan CSS selector
disesuaikan dengan kebutuhannya. Elemen selector akan berlaku pada semua elemen tersebut.
Untuk class dan id selector, akan berlaku pada elemen yang menggunakan class atau id tersebut.
Elemen Selector dideklarasikan berdasarkan tag HTML.

# Class Selector dideklarasikan dengan menambahkan tanda titk (.) sebelum nama class yang akan
digunakan. Kemudian pada tag HTML ditambahkan atribut class dengan value nama class tanpa
menggunakan titik (.). Satu elemen HTML dapat diberikan lebih dari satu class.
<head>
<style>
body {background-color:blue;}
p {font-size:20px; color:mediumblue;}
</style>
</head>

<head>
<link href="style.css" rel="stylesheet" type="text/css">
</head>

<p style="color:blue; font-size:20px;">Pemrograman Web Semester Ganjil</p>

body {color:blue;}
p {font-family:"sans-serif"}
h1 {text-align:center;color:red';}
p {
text-aign:justify;
color:green;
font-size:12pt;
}

Deklarasi CSS
.merah {color:red;}
.serif {font-family:"sans-serif"}
.rata-tengah {text-align:center; font-size:12pt;}
# Penggunaan CSS
<h1 class="merah">Heading berwarna Merah</h1>
<p class="rata-tengah">Paragraf dengan rata tengah</>
<p class"merah serif">paragraf dengan warna merah dan font serif</>
# Modul Praktikum Pemrograman Web
ID Selector dideklarasikan dengan menambahkan tanda # sebelum nama id yang akan digunakan.
Kemudian pada tag HTML ditambahkan atribut id dengan value nama id tanpa menggunakan #.
Satu elemen HTML hanya dapat diberikan satu id.
