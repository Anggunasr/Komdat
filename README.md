# Hastebin

[Sekilas Tentang](#sekilas-tentang) | [Instalasi](#instalasi) | [Pembahasan](#pembahasan) | [Aplikasi Serupa](#aplikasi-serupa) | [Referensi](#referensi)
---:|:---:|:---:|:---:|:---:

## Sekilas Tentang

Hastebin adalah sebuah pastebin, yaitu aplikasi web untuk menyimpan teks. Bersifat open-source, dibuat dengan node.js, sehingga mudah diinstall di network apapun. Hastebin sangat mudah digunakan, cukup dengan menulis atau paste ke scriptnya, kemudian setelah disave akan muncul URL yang berisi teks yang sebelumnya diisikan ke script, dan dapat diakses. Hastebin tampil dengan antarmuka yang simpel dan nyaman dilihat. Teks yang disimpan dalam hastebin akan hilang setelah 30 hari dari saat teks tersebut terakhir dibuka. Teks dapat diubah atau dihapus oleh siapapun.



## Instalasi
[`kembali ke atas`](#Hastebin)
### Kebutuhan
-Apache
-Redis-server

### Cara Instalasi
#### Instalasi aplikasi Hastebin

1. Clone projek haste-server dari repository resmi
```bash
git clone https://github.com/seejohnrun/haste-server.git
```
2. Masuk ke folder haste-server, lalu install npm
```bash
cd haste-server
sudo apt-get install npm
```
4. Install hastebin dari dari intaller yang telah ada di folder haste-server
```bash
npm install
```
5. Jalankan hastebin
```bash
npm start
```
6. Hastebin dapat diakses pada link berikut (http://agrihack.party:7777)

## Cara Pemakaian
[`kembali ke atas`](#Hastebin)
- buka link (http://agrihack.party:7777)
- masukkan teks yang inginkan
- simpan dengan klik ikon save pada bagian kanan atas atau gunakan shorcut ctrl+s
- link dapat disebar melalui twitter dengan klik ikon twitter atau salin manual link yang tergenerate
- editing dapat dilakukan dan akan mengenerate link baru

## Pembahasan
[`kembali ke atas`](#Hastebin)
### Kelebihan
-Tampilan hastebin relatif lebih simpel dan nyaman dilihat dibanding aplikasi pastebin lainnya
-Hastebin dapat mendeteksi bahasa pemrograman yang digunakan pada teks yang dituliskan (jika berupa source code), kemudian akan ditulis di URL dengan ekstensi berupa jenis bahasa pemrograman tersebut (misal: teks SQL disimpan di URL https://hastebin.com/inotoziquy.sql
-Link URL selalu ditulis dengan huruf vokal-konsonan secara bergantian sehingga dapat dibaca.
-Share link via [Twitter](https://twitter.com)

### Kekurangan
-Privasi tidak terjaga, teks dapat diubah dan dihapus oleh siapapun
-Link bertahan selama 30 hari sejak terakhir dibuka
-Tidak dapat melakukan modifikasi link


### Aplikasi Serupa
[`kembali ke atas`](#Hastebin)
#### [Chop](https://chopapp.com)
Chop merupakan aplikasi web penyimpan teks. Chop dapat menangani syntax HTML, CSS, Java, dan lain-lain. Chop sangat mudah dingunakan untuk kolaborasi dengan fitur komentar yang disediakannya.
#### [Pastebin] (https://github.com/lordelph/pastebin)
Pastebin merupakan aplikasi web penyimpan teks secara anonim atau tidak. Pastebin juga dapat deklarasi hightlight syntax yang dapat dipilih secara manual, selain itu pastebin dapat memilih kapan link dapat expired.


## Referensi
[`kembali ke atas`](#Hastebin)
-(https://github.com/seejohnrun/haste-server/wiki)
-(https://github.com/lordelph/pastebin)
