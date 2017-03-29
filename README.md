# Chyrp Lite

[Sekilas Tentang](#sekilas-tentang) | [Instalasi](#instalasi) | [Konfigurasi](#konfigurasi) | [Cara Pemakaian](#cara-pemakaian) | [Aplikasi Serupa](#aplikasi-serupa) | [Referensi](#referensi)
:---:|:---:|:---:|:---:|:---:|:---:

## Sekilas Tentang

Chyrp lite adalah sebuah mesin blogging yang ringan, dikembangkan dengan PHP dan MySQL. Dengan Chyrp Lite, user dapat membuat sebuah blog baik itu blog, baik blog biasa maupun tumbleblog (blog yang postnya dapat berupa audio, quote, link, gambar, atau video).

Terdapat fitur utama Feathers dan Pages. Feather digunakan untuk mengupload file-file multimedia seperti gambar, video, dan sebagainya sehingga blog yang dibuat menjadi seperti tumbleblog. Pages digunakan untuk membuat sebuah post secara terpisah dari blog utama, misal untuk membuat sebuah kategori post yang terpisah. Bisa dikatakan, Chyrp Lite merupakan gabungan dari blog dan tumbleblog.

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

###Kelebihan
Menurut persepektif developer, Chyrp Lite memiliki beberapa kelebihan sebagai berikut:

*Mudah diinstall dan maintain 
Dibandingkan dengan aplikasi serupa, Chyrp dapat dikatakan sebagai aplikasi dengan requirements paling minimal. Cukup dengan PHP 5.2+ serta MySQL 4.1+ atau SQLite 3+, Chyrp Lite bisa didapatkan. Proses instalasi Chyrp Lite juga tidak rumit, mengingat yang diperlukan hanyalah MySQL atau SQLite saja.

*Mudah melakukan pengembangan tema dengan menggunakan Twig template engine
Saat membahas seputar template engine di PHP, banyak orang menduga bahwa PHP merupakan template engine. Akan tetapi, meskipun PHP telah memulai dirinya sebagai template language, sayangnya ia tak berevolusi sehingga masih belum mendukung modern template engine yang banyak dikembangkan kini. Secara umum, Twig memiliki banyak kelebihan untuk digunakan sebagai template engine seperti mudah dimengerti dan dipelajari. Namun kelebihan utama dari Twig yaitu sangat fleksibel untuk memenuhi kebutuhan pengguna karena memiliki open architecture, sehingga pengguna dapat membuat DSL tersendiri. Hal ini tentu membuat pengembangan tema pada Chyrp Lite juga menjadi lebih mudah. 


## Referensi
