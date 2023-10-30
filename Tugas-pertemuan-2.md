<h2>Membuat Tabel mahasiswa pada Database polban</h2>

1. buka SQL Shell di pencarian, lalu tekan enter sampai login.

![image](https://github.com/13AkmalAlf/pertemuan-1-basis-data/assets/148737219/821c7444-a7b7-44d6-a237-1fd5035a55e0)
![image](https://github.com/13AkmalAlf/pertemuan-1-basis-data/assets/148737219/fc030a99-98e1-4a4e-a6f1-ae0c99803248)

3. buat database baru dengan nama polban menggunakan syntax berikut. Lalu connect menggunakan command '\c'.

![image](https://github.com/13AkmalAlf/pertemuan-1-basis-data/assets/148737219/fb836824-b9d5-4b0a-a8b8-d3708fda54c0)

3. sebelum membuat tabel, buatlah type baru bernama gender dengan value L dan P untuk memudahkan memasukkan data gender.

![image](https://github.com/13AkmalAlf/pertemuan-1-basis-data/assets/148737219/efc672d4-f9c3-4463-bbcf-49996922dae5)

4. buat tabel baru bernama mahasiswa dengan isi daftar kolom nim, nama, gender, alamat, kota asal, tanggal lahit, tahun masuk, dan nomor handphone.

![image](https://github.com/13AkmalAlf/pertemuan-1-basis-data/assets/148737219/8bc09b7f-5c4b-45c1-9bc3-ab72779b4cb1)

5. setelah muncul pernyataan 'CREATE TABLE' gunakan syntax 'select * from mahasiswa' untuk memastikan bahwa tabel telah dibuat sesuai keinginan kita.

![image](https://github.com/13AkmalAlf/pertemuan-1-basis-data/assets/148737219/963158e1-a956-4144-9617-374d6362f5a7)

dari gambar diatas, bisa dipastikan bahwa tabel yang ingin kita buat sudah sesuai.

6. lalu untuk memsukkan valuenya gunakan command seperti pada gambar berikut. cobalah dulu untuk mengisi 1 row terlebih dahulu.

![image](https://github.com/13AkmalAlf/pertemuan-1-basis-data/assets/148737219/302acf74-9e5e-4a37-8a37-b4d37e87c3c1)

'insert 0 1' menunjukan bahwa kita berhasil mengisi 1 row dari tabel mahasiswa. setelah itu masukkan semua data yang ingin kita masukkan.

![image](https://github.com/13AkmalAlf/pertemuan-1-basis-data/assets/148737219/25341c47-9784-4c07-9b46-766cc43ab138)

7. terakhir, untuk memastikan apakah semua data telah berhasil diinput, masukkan command 'select * from mahasiswa' lagi.

![image](https://github.com/13AkmalAlf/pertemuan-1-basis-data/assets/148737219/bad71f04-dadd-4f55-85c6-f81610430d37)

Selesai. 

berikut adalah tampilan data tabel pada dBeaver.

![image](https://github.com/13AkmalAlf/pertemuan-1-basis-data/assets/148737219/0dc3ce83-2e27-4850-909d-73aa68477975)





