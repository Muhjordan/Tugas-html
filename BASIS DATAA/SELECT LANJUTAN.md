# AND
## Struktur Query
```Sql
SELECT warna,pemilik FROM mobil WHERE warna="Hitam" AND pemilik="Ibrahim";
```
## Contoh Query 
```sql
SELECT warna,pemilik FROM mobil WHERE warna="Hitam" AND pemilik="Jordan";
```
## Hasil Program
![[IMG_20240220_143229.jpg]]
## Analisis
`SELECT warna, pemilik`: Pernyataan SELECT ini menentukan kolom-kolom mana yang akan diambil dari tabel "mobil", yaitu kolom "warna" dan "pemilik".

`FROM mobil`: Mengidentifikasi tabel yang akan digunakan dalam operasi SELECT, yaitu tabel "mobil".

`WHERE warna="Hitam" AND pemilik="Jordan"`: Klausul WHERE digunakan untuk menerapkan kriteria seleksi pada data yang akan diambil. Dalam hal ini, hanya data yang memiliki nilai "warna" sama dengan "Hitam" dan nilai "pemilik" sama dengan "Jordan" yang akan dipilih
## Kesimpulan 
pernyataan SELECT ini akan mengambil data warna dan pemilik dari tabel "mobil" yang memiliki warna "Hitam" dan pemilik "Jordan".
# OR
## Struktur Query
```sql
SELECT warna,pemilik FROM mobil WHERE warna="Hitam" OR pemilik="Ibrahim";
```
## Contoh Query
```sql
select warna,pemilik from mobil where warna="Hitam" OR pemilik="Jordan";
```
## Hasil Program
![[IMG_20240220_143937.jpg]]
## Analisis
`SELECT warna, pemilik`: Pernyataan SELECT menentukan kolom mana yang akan diambil dari tabel "mobil", yaitu kolom "warna" dan "pemilik".

`FROM mobil`: Mengidentifikasi tabel yang akan digunakan dalam operasi SELECT, yaitu tabel "mobil".

`WHERE warna="Hitam" OR pemilik="Jordan"`: Klausul WHERE digunakan untuk menerapkan kriteria seleksi pada data yang akan diambil. Dalam hal ini, data akan dipilih jika memiliki nilai "warna" sama dengan "Hitam" atau nilai "pemilik" sama dengan "Jordan".
## Kesimpulan 
pernyataan SELECT ini akan mengambil data warna dan pemilik dari tabel "mobil" yang memiliki warna "Hitam" atau pemilik "Jordan".
# BETWEEN
## Struktur Query
```sql
SELECT * FROM mobil WHERE harga_rental BETWEEN 100000 AND 200000;
```
## Contoh Query 
```SQL
select * from mobil where harga_rental BETWEEN 100000 AND 150000;
```
## Hasil Program
![[IMG_20240220_144004.jpg]]
## Analisis
`SELECT` : Pernyataan SELECT ini menunjukkan bahwa kita akan mengambil semua kolom dari tabel "mobil".

`FROM mobil`: Mengidentifikasi tabel yang akan digunakan dalam operasi SELECT, yaitu tabel "mobil".

`WHERE harga_rental BETWEEN 100000 AND 150000`: Klausul WHERE digunakan untuk menerapkan kriteria seleksi pada data yang akan diambil. Dalam hal ini, data akan dipilih jika nilai "harga_rental" berada dalam rentang antara 100.000 dan 150.000.
## Kesimpulan 
pernyataan SELECT ini akan mengambil semua kolom dari tabel "mobil" untuk data yang memiliki nilai "harga_rental" dalam rentang antara 100.000 dan 150.000.
# NOTWEEN
## Struktur Query
```sql
SELECT * FROM mobil WHERE harga_rental NOT BETWEEN 100000 AND 200000;
```
## Contoh Query 
```SQL
select * from mobil where harga_rental NOT BETWEEN 100000 AND 150000;
```
## Hasil Program
![[IMG_20240220_144257.jpg]]
## Analisis
`SELECT` : Pernyataan SELECT ini menunjukkan bahwa kita akan mengambil semua kolom dari tabel "mobil".

`FROM mobil`: Mengidentifikasi tabel yang akan digunakan dalam operasi SELECT, yaitu tabel "mobil".

`WHERE harga_rental NOT BETWEEN 100000 AND 150000`: Klausul WHERE digunakan untuk menerapkan kriteria seleksi pada data yang akan diambil. Dalam hal ini, data akan dipilih jika nilai "harga_rental" tidak berada dalam rentang antara 100.000 dan 150.000.
## Kesimpulan 
pernyataan SELECT ini akan mengambil semua kolom dari tabel "mobil" untuk data yang memiliki nilai "harga_rental" di luar rentang antara 100.000 dan 150.000.
# <=
## Struktur Query
```sql
SELECT FROM * mobil WHERE harga_rental <= 50000;
```
## Contoh Query 
```sql
select * from mobil where harga_rental <= 100000;
```
## Hasil Program
![[IMG_20240220_145125.jpg]]
## Analisis
`SELECT` : Pernyataan SELECT ini menunjukkan bahwa kita akan mengambil semua kolom dari tabel "mobil".

`FROM mobil`: Mengidentifikasi tabel yang akan digunakan dalam operasi SELECT, yaitu tabel "mobil".

`WHERE harga_rental <= 100000`: Klausul WHERE digunakan untuk menerapkan kriteria seleksi pada data yang akan diambil. Dalam hal ini, data akan dipilih jika nilai "harga_rental" kurang dari atau sama dengan 100.000.
## Kesimpulan 
pernyataan SELECT ini akan mengambil semua kolom dari tabel "mobil" untuk data yang memiliki nilai "harga_rental" kurang dari atau sama dengan 100.000.
# >=
## Struktur Query
```sql
SELECT FROM * mobil WHERE harga_rental >= 50000;
```
## Contoh Query 
```sql
select * from mobil where harga_rental >= 100000;
```
## Hasil Program
![[IMG_20240220_145310.jpg]]
## Analisis
`SELECT` : Pernyataan SELECT ini menunjukkan bahwa kita akan mengambil semua kolom dari tabel "mobil".

`FROM mobil`: Mengidentifikasi tabel yang akan digunakan dalam operasi SELECT, yaitu tabel "mobil".

`WHERE harga_rental >= 100000`: Klausul WHERE digunakan untuk menerapkan kriteria seleksi pada data yang akan diambil. Dalam hal ini, data akan dipilih jika nilai "harga_rental" lebih besar dari atau sama dengan 100.000.
## Kesimpulan 
pernyataan SELECT ini akan mengambil semua kolom dari tabel "mobil" untuk data yang memiliki nilai "harga_rental" lebih besar dari atau sama dengan 100.000.
# <> atau !=
## Struktur Query
```sql
SELECT FROM * mobil WHERE harga_rental <> 50000;
```
## Contoh Query 
```sql
select * from mobil where harga_rental <> 100000;
```
## Hasil Program

![[IMG_20240220_145422.jpg]]
## Analisis 
`SELECT` : Ini menunjukkan bahwa kita ingin mengambil semua kolom dari tabel "mobil".
`FROM mobil`: Menunjukkan bahwa kita ingin mengambil data dari tabel "mobil".
`WHERE harga_rental <> 100000`: Ini adalah klausa WHERE yang memfilter data, hanya mengambil baris di mana nilai kolom "harga_rental" tidak sama dengan 100.000.
## Kesimpulan 
semua kolom data dari tabel "mobil" dimana nilai kolom "harga_rental" tidak sama dengan 100.000.

Hasilnya akan mencantumkan semua data mobil yang harga rentalnya berbeda dari 100.000, sehingga akan mencakup semua harga rental kecuali 100.000.
# Tantangan

## Struktur Query
```sql
Select kondisi from nama_tabel where kondisi="":
```

## Contoh Query 
```sql
Select kondisi from mobil where warna="Biru":
```
## Hasil Program
![[IMG_20240301_073930.jpg]]
## Analisis 
`SELECT kondisi`: Menunjukkan bahwa hanya nilai dari kolom "kondisi" yang akan diambil.
`FROM mobil`: Menunjukkan bahwa pengambilan data dilakukan dari tabel "mobil".
`WHERE warna = "Biru"`: Ini adalah klausa WHERE yang berfungsi sebagai filter untuk memilih baris yang memiliki nilai "Biru" di kolom "warna".
## Kesimpulan 
mengambil nilai dari kolom "kondisi" dari tabel "mobil" dimana nilai kolom "warna" adalah "Biru".

Hasilnya akan mencantumkan nilai dari kolom "kondisi" untuk setiap baris yang memiliki nilai "Biru" di kolom "warna" dalam tabel "mobil".
# IN
## Struktur Query
```sql
select * from nama_tabel where data IN('nilai 1','nilai 2');
```
## Contoh Query
```sql
select * from mobil where warna IN('pink','biru');
```
## Hasil
![[IMG_20240301_074423.jpg]]
## Analisis
`SELECT` : Ini menunjukkan bahwa kita ingin mengambil semua kolom dari tabel "mobil".
`FROM mobil`: Menunjukkan bahwa kita ingin mengambil data dari tabel "mobil".
`WHERE warna IN ('pink', 'biru')`: Ini adalah klausa WHERE yang memfilter data, hanya mengambil baris di mana nilai kolom "warna" adalah 'pink' atau 'biru'.
Hasilnya akan mencakup semua data mobil dengan warna 'pink' atau 'biru'.
## Kesimpulan 
pernyataan SELECT ini akan mengambil semua kolom dari tabel "mobil" untuk data yang memiliki nilai "warna" sama dengan 'pink' atau 'biru'.
# IN/AND
## Struktur
```sql
select * from nama_tabel where data IN('nilai 1','nilai 2')AND data 2=nilai 1;
```
## Contoh Query
```sql
select * from mobil where warna IN('pink','biru')AND harga_rental=50000;
```
## Hasil
![[IMG_20240301_074616.jpg]]
## Analisis
`SELECT` : Menunjukkan bahwa kita ingin mengambil semua kolom dari tabel "mobil".
`FROM mobil`: Menunjukkan bahwa pengambilan data dilakukan dari tabel "mobil".
`WHERE warna IN ('pink', 'biru') AND harga_rental = 50000`: Ini adalah klausa WHERE yang berfungsi sebagai filter untuk memilih baris yang memiliki nilai 'pink' atau 'biru' di kolom "warna" dan nilai 50000 di kolom "harga_rental".
## Kesimpulan
pernyataan SELECT ini akan mengambil semua kolom dari tabel "mobil" untuk data yang memiliki nilai "warna" sama dengan 'pink' atau 'biru' dan nilai "harga_rental" sama dengan 50000.
___
# IN/OR

## Struktur
```sql
select * from nama_tabel where data IN('nilai 1','nilai 2')OR data 2=nilai 1;
```
## Contoh Query
```sql
select * from mobil where warna IN('pink','biru')OR harga_rental=50000;
```
## Hasil
![[IMG_20240301_074923.jpg]]
## Analisis
`SELECT` : Pernyataan SELECT ini menunjukkan bahwa kita akan mengambil semua kolom dari tabel "mobil".

`FROM mobil`: Mengidentifikasi tabel yang akan digunakan dalam operasi SELECT, yaitu tabel "mobil".

`WHERE warna IN('pink','biru') OR harga_rental=50000`: Klausul WHERE digunakan untuk menerapkan kriteria seleksi pada data yang akan diambil. Dalam hal ini, data akan dipilih jika nilai kolom "warna" berada dalam daftar nilai yang diberikan ('pink' atau 'biru') atau nilai kolom "harga_rental" sama dengan 50000.
## Kesimpulan
pernyataan SELECT ini akan mengambil semua kolom dari tabel "mobil" untuk data yang memiliki nilai "warna" sama dengan 'pink' atau 'biru' atau nilai "harga_rental" sama dengan 50000.
# IN/AND/OPERATOR
## Struktur
```sql
select * from nama_tabel where data IN('nilai 1','nilai 2')AND data 2<nilai 1;
```
## Contoh Query
```sql
select * from mobil where warna IN('pink','biru')AND harga_rental<100000;
```
## Hasil
![[IMG_20240301_075115.jpg]]
## Analisis
`SELECT` : Pernyataan SELECT ini menunjukkan bahwa kita akan mengambil semua kolom dari tabel "mobil".

`FROM mobil`: Mengidentifikasi tabel yang akan digunakan dalam operasi SELECT, yaitu tabel "mobil".

`WHERE warna IN('pink','biru') AND harga_rental<100000`: Klausul WHERE digunakan untuk menerapkan kriteria seleksi pada data yang akan diambil. Dalam hal ini, data akan dipilih jika nilai kolom "warna" berada dalam daftar nilai yang diberikan ('pink' atau 'biru') dan nilai kolom "harga_rental" kurang dari 100000.
## Kesimpulan
pernyataan SELECT ini akan mengambil semua kolom dari tabel "mobil" untuk data yang memiliki nilai "warna" sama dengan 'pink' atau 'biru' dan nilai "harga_rental" kurang dari 100000.
# LIKE (Mencari awalan)
## Struktur
```sql
select * from nama_tabel where data LIKE 'n%';
```
## Contoh Query
```sql
select * from mobil where pemilik LIKE 'J%';
```
## Hasil
![[IMG_20240301_075443.jpg]]
## Analisis
`SELECT` : Pernyataan SELECT ini menunjukkan bahwa kita akan mengambil semua kolom dari tabel "mobil".

`FROM mobil`: Mengidentifikasi tabel yang akan digunakan dalam operasi SELECT, yaitu tabel "mobil".

`WHERE pemilik LIKE 'J%'`: Klausul WHERE digunakan untuk menerapkan kriteria seleksi pada data yang akan diambil. Dalam hal ini, data akan dipilih jika nilai kolom "pemilik" dimulai dengan huruf 'J' dan diikuti oleh nol atau lebih karakter tambahan.
## Kesimpulan
pernyataan SELECT ini akan mengambil semua kolom dari tabel "mobil" untuk data yang memiliki nilai kolom "pemilik" dimulai dengan huruf 'J'.
# LIKE (Mencari akhir)
## Struktur Query 
```sql
select * from nama_tabel where data LIKE '%n':
```
## Contoh Query
```sql
select * from mobil where pemilik LIKE '%n':
```
## Hasil
![[IMG_20240301_075519.jpg]]
## Analisis
memilih semua baris dari tabel "mobil" di mana nilai kolom "pemilik" berakhir dengan huruf "n". Operator LIKE digunakan dengan pola pencocokan '%n', di mana '%' cocok dengan nol atau lebih karakter apa pun sebelum "n". Misalnya, jika ada entri dengan nilai kolom "pemilik" adalah "Jordan", entri itu akan dipilih karena akhirannya adalah "n"
## Kesimpulan
select * from mobil where pemilik LIKE '%n' digunakan untuk memilih semua baris dari tabel "mobil" di mana nilai kolom "pemilik" berakhir dengan huruf "n". Dengan menggunakan operator LIKE dan pola pencocokan %n
# LIKE (Mencari awalan/akhir)
## Struktur Query 
```sql
Select * from nama_tabel where data LIKE 'J%n';
```
## Contoh Query
```sql
Select * from mobil where pemilik LIKE 'J%n';
```
## Hasil
![[Screenshot_2024-03-26-13-19-11-92 1.jpg]]

## Analisis
SELECT * FROM mobil WHERE pemilik LIKE 'J%n' digunakan untuk memilih semua baris dari tabel "mobil" di mana nilai kolom "pemilik" dimulai dengan huruf "J" dan berakhir dengan huruf apapun setelahnya. Dengan menggunakan operator LIKE dan pola pencocokan 'J%n'
## Kesimpulan
# LIKE(mencari total Karakter)
## Struktur Query 
```sql
Select * from nama_tabel where data LIKE 'n':
```
## Contoh Query
```sql
Select * from mobil where pemilik LIKE 'Jordan':
```
## Hasil

![[Screenshot_2024-03-26-13-19-54-52 1.jpg]]
## Analisis
`SELECT * FROM mobil WHERE pemilik LIKE 'Jordan'` digunakan untuk memilih semua baris dari tabel "mobil" di mana nilai kolom "pemilik" sama dengan "Jordan". Dengan menggunakan operator LIKE dan pola pencocokan 'Jordan',
## Kesimpulan
# LIKE(Kombinasi)
## Struktur Query 
```sql
Select * from nama_tabel where data LIKE '_%':
```
## Contoh Query
```sql
Select * from mobil where pemilik LIKE 'Jordan%':
```
## Hasil
![[Screenshot_2024-03-26-13-20-19-46.jpg]]
## Analisis
SELECT * FROM mobil WHERE pemilik LIKE 'Jordan%' digunakan untuk memilih semua baris dari tabel "mobil" di mana nilai kolom "pemilik" dimulai dengan kata "Jordan". Dengan menggunakan operator LIKE dan pola pencocokan 'Jordan%', program ini mencari data di mana nilai kolom "pemilik" dimulai dengan kata "Jordan" diikuti oleh karakter apa pun atau tanpa karakter tambahan
## Kesimpulan
# NOT LIKE
## Struktur Query 
```sql
Select * from nama_tabel where data NOT LIKE '_%':
```
## Contoh Query
```sql
Select * from mobil where pemilik NOT LIKE 'J%':
```
## Hasil

![[Screenshot_2024-03-26-13-32-08-29.jpg]]
## Analisis
`SELECT * FROM mobil WHERE pemilik NOT LIKE 'J%'` digunakan untuk memilih semua baris dari tabel "mobil" di mana nilai kolom "pemilik" tidak dimulai dengan huruf "J". Dengan menggunakan operator NOT LIKE dan pola pencocokan 'J%'
## Kesimpulan
program ini mencari data di mana nilai kolom "pemilik" tidak dimulai dengan huruf "J".
# NULL 
## Struktur Query 
```sql
select * from nama_tabel where kolom_tabel IS NOT NULL;
```
## Contoh Query
```Sql
select * from mobil where peminjam IS NULL;
```
## Hasil 
![[IMG_20240326_121535.jpg]]
## Kesimpulan
Program SQL tersebut merupakan perintah SELECT yang digunakan untuk mengambil semua data dari tabel "mobil" di mana nilai dalam kolom "pemilik" mengandung huruf "n" di mana pun posisinya.
# NOT NULL
## Struktur Query 
```sql
select * from nama_tabel where kolom_tabel IS NOT NULL;
```
## Contoh Query 
```sql
select * from mobil where peminjam IS NOT NULL;
```
## Hasil 
![[IMG_20240326_122023.jpg]]
## Kesimpulan 
untuk mengambil semua data dari tabel "mobil" di mana kolom "peminjam" tidak kosong (tidak NULL).
# ORDER BY & LIMIT
## ORDER BY
### Struktur Query 
```sql
select * from nama_tabel ORDER BY kolom_tabel ASC;
```
### Contoh Query 
```sql
select * from mobil ORDER BY pemilik ASC;
```
## Hasil
![[IMG_20240326_122454.jpg]]
## Kesimpulan
Perintah SQL tersebut digunakan untuk mengambil semua data dari tabel "mobil" dan mengurutkannya berdasarkan nilai pada kolom "pemilik" secara menaik (ASC).
## Struktur Query
```sql
select * from nama_tabel ORDER BY kolom_tabel ASC;
```
## Contoh Query 
``` sql
select * from mobil ORDER BY peminjam ASC;
```
## Hasil
![[IMG_20240326_122746.jpg]]
## Kesimpulan 
Perintah SQL tersebut digunakan untuk mengambil semua data dari tabel "mobil" dan mengurutkannya berdasarkan nilai pada kolom "peminjam" secara menaik (ASC).
## LIMIT
### Contoh Query 
```Sql
SELECT * FROM mobil WHERE warna = ”Hitam” ORDER BY harga ASC LIMIT 2;
```

# DISTINCT
## Struktur Query 
```sql
select distinct (kolom_tabel) from nama_tabel;
```
## Contoh Query 
```sql
select distinct (pemilik) from mobil;
```
## Hasil
![[IMG_20240326_130639.jpg]]
## Kesimpulan 
Perintah SQL tersebut digunakan untuk mengambil nilai unik dari kolom "pemilik" dalam tabel "mobil".

## Contoh Query 
```sql
select distinct (harga_rental) from mobil ORDER BY harga_rental desc;
```
## Hasil
![[IMG_20240326_130908.jpg]]
## Kesimpulan 
Perintah SQL tersebut digunakan untuk mengambil nilai unik dari kolom "harga_rental" dalam tabel "mobil", kemudian hasilnya diurutkan secara menurun (descending) berdasarkan nilai harga_rental.
