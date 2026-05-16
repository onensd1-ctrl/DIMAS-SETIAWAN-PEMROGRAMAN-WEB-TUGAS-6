# DIMAS-SETIAWAN-PEMROGRAMAN-WEB-TUGAS-6
[index.html](https://github.com/user-attachments/files/27851932/index.html)

<!DOCTYPE html>
<html lang="id">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Tugas Pertemuan 6</title>

    <link rel="stylesheet" href="style.css">
</head>

<body>

    <div class="container">
        <h1>Tugas Pertemuan 6 - JavaScript Dasar</h1>

        <!-- 1 Biodata -->
        <div class="card">
            <h2>1. Program Biodata</h2>

            <input type="text" id="nama" placeholder="Masukkan Nama">
            <input type="number" id="umur" placeholder="Masukkan Umur">

            <button onclick="biodata()">Tampilkan Biodata</button>

            <div class="hasil" id="hasilBiodata"></div>
        </div>

        <!-- 2 Kalkulator -->
        <div class="card">
            <h2>2. Kalkulator Sederhana</h2>

            <input type="number" id="angka1" placeholder="Masukkan Angka Pertama">
            <input type="number" id="angka2" placeholder="Masukkan Angka Kedua">

            <button onclick="kalkulator()">Hitung</button>

            <div class="hasil" id="hasilKalkulator"></div>
        </div>

        <!-- 3 Nilai -->
        <div class="card">
            <h2>3. Perhitungan Nilai</h2>

            <input type="number" id="nilai1" placeholder="Nilai 1">
            <input type="number" id="nilai2" placeholder="Nilai 2">
            <input type="number" id="nilai3" placeholder="Nilai 3">

            <button onclick="hitungRata()">Hitung Rata-rata</button>

            <div class="hasil" id="hasilNilai"></div>
        </div>

        <!-- 4 Konversi Suhu -->
        <div class="card">
            <h2>4. Konversi Suhu</h2>

            <input type="number" id="celsius" placeholder="Masukkan Suhu Celsius">

            <button onclick="konversiSuhu()">Konversi</button>

            <div class="hasil" id="hasilSuhu"></div>
        </div>

        <!-- 5 Kasir -->
        <div class="card">
            <h2>5. Kasir Sederhana</h2>

            <input type="text" id="barang" placeholder="Nama Barang">
            <input type="number" id="harga" placeholder="Harga Barang">
            <input type="number" id="jumlah" placeholder="Jumlah Barang">

            <button onclick="kasir()">Hitung Total</button>

            <div class="hasil" id="hasilKasir"></div>
        </div>

        <!-- 6 Luas Persegi Panjang -->
        <div class="card">
            <h2>6. Luas Persegi Panjang</h2>

            <input type="number" id="panjang" placeholder="Masukkan Panjang">
            <input type="number" id="lebar" placeholder="Masukkan Lebar">

            <button onclick="luasPersegi()">Hitung Luas</button>

            <div class="hasil" id="hasilLuas"></div>
        </div>
    </div>

    <script src="PEMROGRAMAN WEB TUGAS 6\script.js"></script>
</body>

</html>
