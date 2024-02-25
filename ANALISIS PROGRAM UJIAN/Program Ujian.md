## Program
```html
<table height="100%" width="100%">
  <tr>
    <th colspan="2" bgcolor="yellow" align="left" height="50">
      Flower Shop</th>
  </tr>
  <tr>
    <th colspan="2"align="center">
      <h1>Selamat Datang Di Flower Shop</h1>
    </th>
  </tr>
  <tr>
    <th colspan="2" align="center">
    <img src="" alt="toko bunga" height="410" width="410">
    </th>
  </tr>
  <tr>
    <th colspan="2" align="center">
      <button>Order Now!</button>
  </tr>
  <tr>
   <td align="center" bgcolor="aqua">
     <a href="">Lihat Daftar Bunga</a>
   </td> 
    <td align="center" bgcolor="aqua">
      <a href="">Pesan Bunga Segera</a>
    </td>
  </tr>

</table>
```
### Analisis
**==Index.html==**:
``<table height="100%" width="100%">``: Ini adalah tag pembuka untuk tabel HTML dengan atribut height dan width diatur ke 100% untuk mengisi seluruh lebar dan tinggi layar.

``<tr>``: Ini adalah tag untuk baris pada tabel.

``<th colspan="2" bgcolor="yellow" align="left" height="50">Flower Shop</th>``: Ini adalah header untuk judul toko bunga dengan atribut colspan="2" untuk menggabungkan dua kolom, bgcolor="yellow" untuk mengatur warna latar belakang menjadi kuning, align="left" untuk penataan teks ke kiri, dan height="50" untuk ketinggian baris.

``<tr>``: Baris baru dalam tabel.

``<th colspan="2"align="center"><h1>Selamat Datang Di Flower Shop</h1></th>``: Ini adalah header dengan judul "Selamat Datang Di Flower Shop" yang diatur dengan colspan="2" untuk menggabungkan dua kolom, align="center" untuk penataan teks ke tengah, dan h1 untuk memberikan format judul yang lebih besar.

``<tr>``: Baris baru dalam tabel.

``<th colspan="2" align="center"><img src="" alt="toko bunga" height="410" width="410"></th>``: Ini adalah tag gambar untuk gambar toko bunga yang diatur dengan colspan="2" untuk menggabungkan dua kolom, align="center" untuk penataan gambar ke tengah, dan atribut src, alt, height, dan width yang kosong yang perlu diisi dengan informasi gambar yang sebenarnya.

``<tr>``: Baris baru dalam tabel.
``<th colspan="2" align="center"><button>Order Now!</button></th>``: Ini adalah tombol pesanan dengan teks "Order Now!" yang diatur dengan colspan="2" untuk menggabungkan dua kolom dan align="center" untuk penataan tombol ke tengah.

``<tr>``: Baris baru dalam tabel.

``<td align="center" bgcolor="aqua"><a href="">``Lihat Daftar Bunga`</a></td>``: Ini adalah sel pada kolom pertama dengan latar belakang berwarna "aqua", teks "Lihat Daftar Bunga" yang diatur dengan align="center" untuk penataan teks ke tengah, dan hyperlink kosong yang perlu diisi dengan URL yang sesuai.

``<td align="center" bgcolor="aqua"><a href="">``Pesan Bunga Segera``</a></td>``: Ini adalah sel pada kolom kedua dengan latar belakang berwarna "aqua", teks "Pesan Bunga Segera" yang diatur dengan align="center" untuk penataan teks ke tengah, dan hyperlink kosong yang perlu diisi dengan URL yang sesuai.
## Program
**==List Bunga=**:
```html
<!DOCTYPE html>
<html lang="en">

<head>
    <title>Daftar bunga</title>
</head>
<body>
    <h1>List Bunga</h1>
    <table border="1">
        <tr>
            <th>
                <b>Bunga 1</b><br>
                <img src="1.jpg" height="120" widht="120">
            </th>
            <td>
                <ul>
                    <li>Asal:<b>Gunung bawakaraeng</b></li>
                    <li>Keharuman:<b>Tahan lama</b></li>
                    <li>Harga:<b>Rp. 75.000</b></li>
                </ul>
            </td>
            <th>
                <b>Bunga 4</b><br>
                <img src="2.jpg" height="120" widht="120">
            </th>
            <td>
                <ul>
                    <li>Asal:<B>danau toba</B></li>
                    <li>Keharuman:<b>sedang</b></li>
                    <li>Harga:<b>Rp. 50.000</b></li>
                </ul>
            </td>
        </tr>
        <tr>
            <th>
                <b>Bunga 2</b><br>
                <img src="3.jpg" height="120" widht="120">
            </th>
            <td>
                <ul>
                    <li>Asal:<b>Taman pakui</b></li>
                    <li>Keharuman:<b>Biasa</b></li>
                    <li>Harga:<b>Rp. 20.000</b></li>
                </ul>
                </td>
            <th>
                <b>Bunga 5</b><br>
                <img src="4.jpg" height="120" widht="120">
            </th>
            <td>
                <ul>
                    <li>Asal:<b>Taman macan</b></li>
                    <li>Keharuman:<b>tahan lama</b></li>
                    <li>Harga:<b>Rp. 80.000</b></li>
                </ul>
            </td>
        </tr>
        <th>
            <b>Bunga 3</b><br>
            <img src="5.jpg" height="120" widht="120">
        </th>
        <td>
            <ul>
                <li>Asal:<b>Taman bunga</b></li>
                <li>Keharuman:<b>Sedang</b></li>
                <li>Harga:<b>90.000</b></li>
            </ul>
            </td>
            <th colspan="2" align="center" bgcolor="grey">-</th>
            <tr>
            <th colspan="4" bgcolor="red">
            <a href="orderan_bunga.html" >pesan bunga</a>
            </th>
            </tr>

   
    </tr>
    </table><br>
    <a href="indexbunga.html">Kembali ke Home</a>
    <a href="orderan_bunga.html">pesan bunga</a>
   
</body>
</html>
```
### Analisis
<!DOCTYPE html>: Mendefinisikan tipe dokumen sebagai dokumen HTML5.
``<html lang="en">``: Tag pembuka untuk elemen HTML dengan atribut lang yang menetapkan bahasa ke bahasa Inggris.
``<head>``: Memulai bagian kepala dokumen HTML yang berisi metadata seperti judul halaman.
``<title>Daftar bunga</title>``: Menetapkan judul halaman menjadi "Daftar bunga".
``<body>``: Memulai konten utama halaman.
``<h1>List Bunga</h1>``: Judul utama halaman yang menampilkan teks "List Bunga".
``<table border="1">``: Mulai tabel dengan atribut border yang menetapkan tebal garis tepi tabel menjadi 1 pixel.
``<tr>``: Mulai baris pertama tabel.
``<th>``: Mulai sel header pertama yang berisi informasi tentang "Bunga 1".
``<b>Bunga 1</b>``: Membuat teks "Bunga 1" menjadi tebal.
``<img src="1.jpg" height="120" widht="120">``: Menampilkan gambar "1.jpg" dengan tinggi dan lebar 120 piksel.
``<td>``: Mulai sel data pertama yang berisi informasi tentang "Bunga 1".
``<ul>``: Mulai daftar tak terurut.
``<li>Asal:<b>Gunung bawakaraeng</b></li>``: Item dalam daftar yang menunjukkan asal bunga.
``<li>Keharuman:<b>Tahan lama</b></li>``: Item dalam daftar yang menunjukkan keharuman bunga.
``<li>Harga:<b>Rp. 75.000</b></li>``: Item dalam daftar yang menunjukkan harga bunga.
Dan seterusnya untuk setiap bunga dan informasinya.
``<th colspan="2" align="center" bgcolor="grey">-</th>``: Sel header yang berisi tanda hubung (-) yang memiliki dua kolom yang digabung dan diatur ke tengah dengan latar belakang abu-abu.
``<th colspan="4" bgcolor="red">``: Sel header yang berisi tautan "pesan bunga" dengan empat kolom dan latar belakang merah.
``<a href="indexbunga.html">Kembali ke Home</a>``: Tautan untuk kembali ke halaman utama.
``<a href="orderan_bunga.html">pesan bunga</a>``: Tautan untuk memesan bunga.
## Program
**==Order Bunga==**
```html
<!DOCTYPE html>
<html>
    <head>
        <title>Order_bunga</title>
    </head>
    <body>
        <h1> Pesan bunga</h1>
        <form>
            <b>nama:</b><br>
            <input type="text"></label><br>
            <br>

            <b>jenis bunga:</b><br>
            <select>
                <option>bunga 1</option>
                <option>bunga 2</option>
                <option>bunga 3</option>
                <option>bunga 4</option>
                <option>bunga 5</option>
            </select><br>
            <br>

            <b>jenis pembayaran</b><br>
            <input type="radio" name="jp">
            <label>Tunai</label>

            <input type="radio" name="jp">
            <label>Transfer</label><br>
            <br>

            <b>Alamat pengiriman</b><br>
            <textarea cols="30" rows="5"></textarea><br>
            <br>

            <label><b>Waktu Pengiriman</b></label><br>
            <input type="checkbox">
            <label>pagi</label>
            <input type="checkbox">
            <label>siang</label>
            <input type="checkbox">
            <label>sore</label>
            <input type="checkbox">
            <label>malam</label><br>
            <br>

            <input type="submit" value="Pesan">
            <input type="submit" value="Hapus"><br>
            <hr></hr><br>
            
            <a href="listbunga.html">lihat daftar bunga</a>
            <a href="indexbunga.html">kembali ke home</a>
        </form>
    </body>
</html>
```
### Analisis
<!DOCTYPE html>: Mendefinisikan tipe dokumen sebagai dokumen HTML.
``<html>``: Tag pembuka untuk elemen HTML.
``<head>``: Memulai bagian kepala dokumen HTML yang berisi metadata seperti judul halaman.
``<title>Order_bunga</title>``: Menetapkan judul halaman menjadi "Order_bunga".
``<body>: Memulai konten utama halaman.
``<h1> Pesan bunga</h1>``: Judul utama halaman yang menampilkan teks "Pesan bunga".
``<form>``: Mulai formulir untuk pengguna mengisi pesanan bunga.
``<b>nama:</b><br>``: Label untuk input nama pelanggan.
``<input type="text">``: Kotak input teks untuk pengguna memasukkan nama.
``<b>jenis bunga:</b><br>``: Label untuk pilihan jenis bunga.
``<select>``: Mulai dropdown untuk memilih jenis bunga.
``<option>bunga 1</option>``: Opsi pertama dalam dropdown untuk memilih bunga 1.
Dan seterusnya untuk setiap opsi bunga.
``<b>jenis pembayaran</b><br>|: Label untuk pilihan jenis pembayaran.
``<input type="radio" name="jp">``: Tombol radio untuk memilih pembayaran tunai.
``<label>Tunai</label>``: Label untuk pembayaran tunai.
``<input type="radio" name="jp">``: Tombol radio untuk memilih pembayaran transfer.
``<label>Transfer</label><br>``: Label untuk pembayaran transfer.
``<b>Alamat pengiriman</b><br>``: Label untuk input alamat pengiriman.
``<textarea cols="30" rows="5"></textarea><br>``: Area teks besar untuk pengguna memasukkan alamat pengiriman.
``<label><b>Waktu Pengiriman</b></label><br>``: Label untuk pilihan waktu pengiriman.
``<input type="checkbox">``: Kotak centang untuk memilih waktu pengiriman pagi.
``<label>pagi</label>``: Label untuk waktu pengiriman pagi.
Dan seterusnya untuk setiap waktu pengiriman.
``<input type="submit" value="Pesan">``: Tombol submit untuk mengirim pesanan.
``<input type="submit" value="Hapus"><br>``: Tombol submit untuk menghapus input.
``<hr></hr><br>``: Garis horizontal untuk memisahkan bagian formulir dengan tautan di bawahnya.
``<a href="listbunga.html">lihat daftar bunga</a>``: Tautan untuk melihat daftar bunga.
``<a href="indexbunga.html">kembali ke home</a>``: Tautan untuk kembali ke halaman utama.