# ALTER
## Struktur Query 
```sql
ALTER TABLE nama_kolom ADD batas_peminjaman Tipe data AFTER peminjam;
```
## Contoh Query 
```sql
ALTER TABLE mobil ADD batas_peminjaman varchart(10) AFTER peminjam;
```
### Before
![[IMG_20240423_134638.jpg]]
### After
![[IMG_20240423_134705.jpg]]
### Analisis
### kesimpulan 
### Tambahan
![[IMG_20240423_143456.jpg]]
# Mengubah nama kolom
## Struktur Query 
```sql
ALTER TABLE Nama_tabel RENAME COLUMN Nama_kolom TO deadline;
```
## Contoh Query 
```sql
ALTER TABLE mobil RENAME COLUMN batas_peminjaman TO deadline;
```
### Before
![[IMG_20240423_134705 2.jpg]]
### After
![[IMG_20240423_143032.jpg]]

# Mengubah tipe data kolom
## Struktur Query 
```sql

```
## Contoh Query 
```sql
ALTER TABLE mobil MODIFY deadline DATE;
```

### Before
![[IMG_20240423_143032 1.jpg]]
### After
![[IMG_20240423_145059.jpg]]
# Menambahkan constraint
## Contoh Query 
```sql
ALTER TABLE mobil
ALTER deadline SET DEFAULT ’Ready’;
```
### Before
![[IMG_20240423_145645.jpg]]
### After
![[IMG_20240423_145721.jpg]]
# Menghapus constraint 
## Struktur Query 
## Contoh Query 
```Sql
ALTER TABLE mobil
ALTER deadline DROP DEFAULT;
```
### Before
![[IMG_20240423_152321.jpg]]
### After
![[IMG_20240423_152430.jpg]]
# Menghapus kolom
## Contoh Query
```Sql
ALTER TABLE mobil DROP COLUMN deadline;
```
### Before
![[IMG_20240423_152430 1.jpg]]
### After
![[IMG_20240423_153240.jpg]]
# Mengubah Nama tabel
## Contoh Query 
```sql
ALTER TABLE mobil RENAME TO data_mobil;
```