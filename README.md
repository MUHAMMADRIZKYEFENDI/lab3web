# lab3web
# pembuatan form login 
```
<form action="proses.php" method="post"> 
<fieldset> 
<legend>Login</legend> 
<p> 
<label for="uname">Username</label> 
<input type="text" id="uname" name="username"> 
</p> 
<p> 
<label for="passwd">Password</label> 
<input type="password" id="passwd" name="password"> 
</p> 
<p><input type="submit" value="Login"></p> 
</fieldset> 
</form>
```
Modul Praktikum Pemrograman Web 

![Login page](https://github.com/user-attachments/assets/45c49b8a-e5fe-4d46-833b-fcfac09d6cd3)
# Membuat Ordered List
```
<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>HTML Lanjutan</title>
</head>

<body>
    <header>
        <h1>Membuat List</h1>
    </header>
</body>

</html>
<section id="order-list">
    <h2>Ordered List</h2>
    <ol>
        <li>Pemrograman Web</li>
        <li>Sistem Informasi</li>
        <li>Basis Data 2</li>
    </ol>
</section>\
```
Modul Praktikum Pemrograman Web 

![ordered list](https://github.com/user-attachments/assets/9ba13469-976f-4b91-aa8f-638c62d47ded)
# Membuat Unorderd List 
```
<section id="unorder-list">
    <h2>Unordered List</h2>
    <ul type="square">
        <li>Jaringan Komputer</li>
        <li>Struktur Data</li>
        <li>Algoritma &amp; Pemrograman</li>
    </ul>
</section>
```
Modul Praktikum Pemrograman Web 

![unordered list](https://github.com/user-attachments/assets/8e50f62b-6f67-4173-adb0-58a61c01b118)
# Membuat Description List
```
<section id="unorder-list">
    <h2>Description List</h2>
    <dl>
        <dt>Fakultas Teknik</dt>
        <dd>Teknik Industri</dd>
        <dd>Teknik Informatika</dd>
        <dd>Teknik Lingkungan</dd>
        <dt>Fakultas Ekonomi dan Bisnis</dt>
        <dd>Akuntansi</dd>
        <dd>Manajemen</dd>
        <dd>Bisnis Digital</dd>
    </dl>
</section>
```
Modul Praktikum Pemrograman Web 

![description list](https://github.com/user-attachments/assets/589720d7-ffbd-4794-9050-0412e77ddf46)
# Membuat Tabel
```
<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>HTML Lanjutan</title>
</head>

<body>
    <header>
        <h1>Membuat Table</h1>
    </header>
</body>

</html>
<table border="1" cellpadding="4" cellspacing="0">
    <thead>
        <tr>
            <th>No.</th>
            <th>Fakultas</th>
            <th>Program Studi</th>
        </tr>
    </thead>
    <tbody>
        <tr>
            <td>1.</td>
            <td>Teknik</td>
            <td>Teknik Informatika</td>
        </tr>
        <tr>
            <td>2.</td>
            <td>Teknik</td>
            <td>Teknik Industri</td>
        </tr>
        <tr>
            <td>3.</td>
            <td>Teknik</td>
            <td>Teknik Lingkungan</td>
        </tr>
    </tbody>
</table>
```
Modul Praktikum Pemrograman Web 

![table](https://github.com/user-attachments/assets/5d109651-3a0e-4d67-9bfd-94c2f0ba2891)
# Mengatur Margin dan Padding 
Untuk mengatur margin dan padding pada cel data, tambahkan atribut cellpadding dan 
cellspacing pada tag table. 
```
<table border="1" cellpadding="4" cellspacing="0">
```
Modul Praktikum Pemrograman Web 

![cell padding](https://github.com/user-attachments/assets/f0096d52-0e5d-4d7a-95fe-4b5f1c499622)
# Menggabungkan Sel Data 
Untuk menggabungkan sel data, gunakan atribut rowspan dan colspan. Atribut rowspan untuk 
menggabungkan baris (secara vertikal) dan colspan untuk menggabungkan kolom (secara 
horizontal).
```
<table border="1" cellpadding="6" cellspacing="0">
    <thead>
        <tr>
            <th>No.</th>
            <th>Fakultas</th>
            <th>Program Studi</th>
        </tr>
    </thead>
    <tbody>
        <tr>
            <td>1.</td>
            <td rowspan="3">Teknik</td>
            <td>Teknik Informatika</td>
        </tr>
        <tr>
            <td>2.</td>
            <td>Teknik Industri</td>
        </tr>
        <tr>
            <td>3.</td>
            <td>Teknik Lingkungan</td>
        </tr>
    </tbody>
</table>
```
Modul Praktikum Pemrograman Web

![penggabungan sel](https://github.com/user-attachments/assets/3ac1247e-be66-47b0-9f45-fdeba3744c68)
# Membuat Form 
```
<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>HTML Lanjutan</title>
</head>

<body>
    <header>
        <h1>Membuat Form</h1>
    </header>
</body>

</html>
<form action="proses.php" method="post">
    <fieldset>
        <legend>Data Pelanggan</legend>
        <p>
            <label for="nama">Nama</label>
            <input type="text" id="nama" name="nama">
        </p>
        <p>
            <label for="alamat">Alamat</label>
            <textarea id="alamat" name="alamat" cols="20" rows="3"></textarea>
        </p>
        <p>
            <label>Jenis Kelamin</label>
            <input id="jk_l" type="radio" name="kelamin" value="L" /><label for="jk_l">Laki-laki</label>
            <input id="jk_p" type="radio" name="kelamin" value="P" /><label for="jk_p">Perempuan</label>
        </p>
        <p><input type="submit" value="Login"></p>
    </fieldset>
</form>
```
Modul Praktikum Pemrograman Web

![form](https://github.com/user-attachments/assets/7855666c-b3af-42f2-94de-500d04e7d482)
# Menabahkan Style pada Form 
Agar tampilan form lebih menarik, bisa ditambahkan CSS seperti berikut. 
```
<style> 
form p > label { 
display: inline-block; 
width: 100px; 
} 
form input[type="text"], form textarea { 
border: 1px solid #197a43; 
} 
form input[type="submit"] { 
border: 1px solid #197a43; 
background-color: #197a43; 
color: #ffffff; 
font-weight: bold; 
padding: 5px 15px; 
} 
</style>
```
Modul Praktikum Pemrograman Web 

![form css](https://github.com/user-attachments/assets/c96af872-6ca3-45da-b96a-85956e59feba)
