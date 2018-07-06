
# Aplikasi Persediaan Barang

Aplikasi Persediaan barang ini dibangun menggunakan bahasa pemrograman PHP dan database MySQL. Untuk cara mengakses databasenya menggunakan MySQLi Extension  dengan konsep pemrograman prosedural.

Materi yang dapat dipelajari dari aplikasi ini selain proses create, read, update, delete, dan search adalah bagaimana menggunakan JQuery DataTables untuk membuat tabel yang dinamis, dan membuat laporan dalam format PDF menggunakan library html2pdf. Selain itu juga dapat dipelajari bagaimana mendesain tampilan aplikasi menggunakan CSS Bootstrap. Pada aplikasi ini saya menggunakan template AdminLTE-2.0.4.

# Fitur Apilkasi


1. Login,
Halaman login multi user. Ada 3 level user yaitu Super Admin, Manajer dan Gudang.
2. Data Barang,
Halaman untuk mengolah data barang yang ada pada gudang. Pada halaman ini user dapat menginput, mengubah, menghapus, dan mencari data barang.
3. Data barang Masuk,
Halaman untuk mengolah data barang masuk. Pada halaman ini user dapat menginput, dan mencari data barang masuk.
4. Laporan Stok barang,
Halaman untuk melihat stok barang dan mencetak laporan stok barang. Laporan dapat dicetak per hari, per minggu, per bulan dan per tahun dalam format PDF.
5. Laporan barang Masuk,
Halaman untuk mencetak laporan barang masuk. Laporan dapat dicetak per hari, per minggu, per bulan dan per tahun dalam format PDF.
6. Manajemen User,
Halaman untuk mengolah data user yang dapat menggunakan aplikasi.
7. Ubah Password,
Halaman untuk mengubah password user.


Untuk menggunakan aplikasi ini silakan lakukan beberapa konfigurasi terlebih dahulu.

- Konfigurasi database sistem: buka folder **config** -> **database.php** lalu setting databasenya.
- Konfigurasi database sistem: buka folder **class** -> **class.php** lalu setting databasenya.
- Konfigurasi cetafakturkeluar : buka file **cetakfakturkeluar.php** lalu setting databasenya.
- Konfigurasi exportexcel : buka file **export.php** lalu setting databasenya.

Untuk tampilan terbaik, gunakan browser Google Chrome versi terbaru.
