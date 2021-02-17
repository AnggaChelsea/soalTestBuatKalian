# soalTestBuatKalian

# README #

### Langkah pengerjaan: ###

1. Clone repository ini
2. Kerjakan soal-soal dibawah
3. **Buat branch anda dan lakukan commit pada branch buatan anda sendiri**
4. Push branch anda ke repository ini

-----------------------

### Berikut adalah soal yang harus anda kerjakan: ###

1. Buatlah halaman penghitungan kasir dengan kriteria sebagai berikut:
	* Terdapat field input untuk jumlah uang yang harus dibayarkan (hanya input angka).
	* Terdapat field input untuk jumlah uang yang diberikan oleh pembeli (hanya input angka).
	* Berikan notifikasi jika jumlah uang yang diberikan oleh pembeli bernilai kurang dari uang yang harus dibayarkan.
	* Terdapat sebuah tombol generate dengan kriteria berikut:
		* Ubah menjadi 'disabled' ketika salah satu dari kedua field input kosong.
		* Ubah menjadi 'disabled' ketika jumlah uang yang diberikan oleh pembeli bernilai kurang dari uang yang harus dibayarkan.
	* Ketika tombol generate diklik akan menghasilkan penghitungan selisih uang kembalian:
		* Ubah nominal tersebut menjadi nilai terbilang (misal: 5.000 -> 'lima ribu rupiah').
		* Ubah nominal tersebut menjadi lembaran uang yang harus diambil oleh kasir (misal: 3.500 -> '1x lembaran 2.000, 1x lembaran 1.000, dan 1x koin 500').

2. Buatlah halaman yang menggambar Provinsi di Indonesia menggunakan leaflet.js dari sebuah file geojson.
	* Gunakan data geojson dari https://raw.githubusercontent.com/mfhanif/peta-indonesia-geojson/master/indonesia-prov.geojson
	* Jika sebuah Provinsi diklik maka tampilkan popup berisikan Id, Kode dan Nama Provinsi.
	* Buat fitur mengganti warna suatu Provinsi tertentu menggunakan color picker (gunakan cara yang paling mudah menurut anda).

3. Buatlah sebuah halaman yang dapat menampilkan katalog hewan dengan kriteria berikut (data terdapat pada file 'dataAnimals'):
	* Buatlah card berisikan gambar dan nama seluruh hewan.
	* Terdapat field search untuk melakukan filter data hewan yang tampil.
	* Apabila sebuah data di klik, maka akan mucul popup detil dengan menampilakan gambar, nama, class, dan deskripsi hewan tsb.
	* Tampilan halaman harus menggunakan prinsip responsive design.

### Keterangan: ###

* Kerjakan soal tersebut pada file yang telah disediakan sesuai dengan nomor soal.
* Kerjakan soal tersebut dengan tampilan semenarik mungkin.
* Gunakanlah modul-modul directive angular, terutama untuk soal nomor 1 dan 3.
