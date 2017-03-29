# Chyrp Lite

[Sekilas Tentang](#sekilas-tentang) | [Instalasi](#instalasi) | [Konfigurasi](#konfigurasi) | [Cara Pemakaian](#cara-pemakaian) | [Aplikasi Serupa](#aplikasi-serupa) | [Referensi](#referensi)
:---:|:---:|:---:|:---:|:---:|:---:

## Sekilas Tentang


## Instalasi
### Kebutuhan
  - PHP 5.3.2+
  - MySQL:
    - MySQL 4.1+
    - MySQLi or PDO
  - SQLite:
    -SQLite 3+
    -PDO
### Cara Instalasi
 [chirp lite] (https://github.com/xenocrat/chyrp-lite/archive/v2017.01.tar.gz)
    
## Cara Pemakaian

## Pembahasan

### Kelebihan
Menurut persepektif developer, Chyrp Lite memiliki beberapa kelebihan sebagai berikut:

- Dibandingkan dengan aplikasi serupa, Chyrp dapat dikatakan sebagai aplikasi dengan requirements paling minimal. Cukup dengan PHP 5.2+ serta MySQL 4.1+ atau SQLite 3+, Chyrp Lite bisa didapatkan. Proses instalasi Chyrp Lite juga tidak rumit, mengingat yang diperlukan hanyalah MySQL atau SQLite saja.

- Saat membahas seputar template engine di PHP, banyak orang menduga bahwa PHP merupakan template engine. Akan tetapi, meskipun PHP telah memulai dirinya sebagai template language, sayangnya ia tak berevolusi sehingga masih belum mendukung modern template engine yang banyak dikembangkan kini. Secara umum, Twig memiliki banyak kelebihan untuk digunakan sebagai template engine seperti mudah dimengerti dan dipelajari. Namun kelebihan utama dari Twig yaitu sangat fleksibel untuk memenuhi kebutuhan pengguna karena memiliki open architecture, sehingga pengguna dapat membuat DSL tersendiri. Hal ini tentu membuat pengembangan tema pada Chyrp Lite juga menjadi lebih mudah. 

- Apabila dibandingkan dengan Chyrp, seperti namanya Chyrp Lite lebih efisien dan lebih dapat diandalkan.

### Kekurangan
- Meskipun mendeklarasikan diri sebagai hasil rekonstruksi agresif dari Chyrp, secara umum Chyrp Lite tidak memiliki kelebihan signifikan dibandingkan Chyrp.

-Text editor dari Chyrp Lite tidak terdapat WYSIWYG (yang memungkinkan user melihat hasil akhir interface dari sebuah post sembari user tersebut mengedit postnya)

### Aplikasi Serupa
#### [Bludit](https://github.com/dignajar/bludit) 
Bludit merupakan sebuah aplikasi web sederhana yang digunakan untuk membuat blog maupun situs pribadi hanya dalam singkat. Bludit merupakan aplikasi gratis dan open source. Sama seperti Chyrp, Bludit merupakan platform blog berbasis PHP serta telah memiliki lisensi MIT. 

Salah satu kelebihan dari Bludit yaitu penggunaan flat-files untuk penyimpanannya, sehingga tak perlu lagi melakukan install maupun konfigurasi database. Kelebihan lainnya yaitu adanya fitur Cli Mode (Command line Interface Mode) dimana pengguna dapat membuat, mengubah atau menghapus pages atau posts tanpa harus melalui tampilan web.

## Referensi
1. [What can Chyrp Lite do for me?](https://chyrplite.net) - Chyrplite
2. [Why yet another template engine?](http://twig.sensiolabs.org/) - Twig
3. [Introduction | Bludit ](https://github.com/dignajar/bludit) - Bludit
