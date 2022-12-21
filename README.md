# Lab12web
# Risyad Bima Nugraha
# 312110039
# TI.21.B1
## Membuat Pencarian Data

Untuk membuat pencarian data, yang perlu di perhatikan adalah penggunaan filter pada query data.
<br>
Pada data awal, query untuk menampilkan semua data adalah:
<br>
$sql = “SELECT * FROM data_barang”;

<br>

untuk menambahkan pencarian, maka query tersebut harus ditambahkan klausa WHERE sebagai filter, sehingga menjadi:
<br>
$sql = “SELECT * FROM data_barang WHERE nama = ‘{$var_nama}’”;
<br>
Atau dapat juga menggunakan LIKE seperti berikut:
<br>
$sql = “SELECT * FROM data_barang WHERE nama LIKE ‘{$var_nama}%’”;
<br>

Prosses Selanjutnya Membuat Form Pencarian

![SS](ss/s1.png)

Sisipkan kode tersebut pada file index.php (daftar barang), sebelum table data dan sesudah tombol
tambah data

![ss](ss/s2.png)

Hasil Dari Proses Tersebut
![ss](ss/s3.png)

Hasil Dari Melakukan Pencarian

![ss](ss/s4.png)

# TERIMAKASI
