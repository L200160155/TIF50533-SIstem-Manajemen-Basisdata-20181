# TIF50533-SIstem-Manajemen-Basisdata-20181
Catatan kuliah semester Ganjil 2018


## Pengumuman

*Tugas pengganti kelas hari Rabu, 14 November 2018*

Buatlah sebuah **store procedure** untuk mendapatkan informasi berikut:

# id_pelanggan | nama_pelanggan | shipped | cancelled

**Kolom dibaca dari tabel**  *customers*

id_pelanggan = customerNumber  (INPUT); nama_pelanggan = customerName (OUTPUT)
 
**Kolom dihitung dari tabel** *Orders*  

shipped = Jumlah order yang terkirim (OUTPUT); cancelled = Jumlah order yang di batalkan (OUTPUT)

**Simpan store procedure tersebut dalam SERVER DATABASE yang telah diberikan**

-------------------------------------------------------- 

## Bahan UTS

1. Database *classicmodels*
2. View 
3. Storeprocedure

note: *open cheatsheet 1 lembar A4*


## [Catatan Kuliah SEMESTER GANJIL 2017](https://github.com/handaga/Database-Management-System-2017)

##  Catatan import data 

1. [Download file asli](https://github.com/bana-handaga/TIF50533-SIstem-Manajemen-Basisdata-20181/blob/master/classicmodels.sql)
2. Hapus baris perintah nomor 26 ( *CREATE DATABASE classicmodels*) dan baris 28 ( *use classicmodels* ) 
3. simpan dengan nama file yang berbeda, misal  **import.sql**
4. Jalankan windows command prompt, dan login ke server database ( Lihat email ketua kelompok )
5. Masuk ke database 'NIM Ketua Kelompok' ( Mysql> use L20016xxxxx )
6. Import tabel dan data dari file **import.sql**   ( Mysql [L20016xxxxx]> source **import.sql** 

