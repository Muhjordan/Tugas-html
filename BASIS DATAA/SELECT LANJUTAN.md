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
# OR
## Struktur Query
```sql
SELECT warna,pemilik FROM mobil WHERE warna="Hitam" OR pemilik="Ibrahim";
```
## Contoh Query
```sql
```select warna,pemilik from mobil where warna="Hitam" OR pemilik="Jordan";
```
## Hasil Program
![[IMG_20240220_143937.jpg]]
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
# Tantangan

## Struktur Query

## Contoh Query 
## Hasil Program