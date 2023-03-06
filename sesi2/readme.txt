yang dipelajari di sesi 2

1. html
2. instalasi vscode
3. menyambungkan vscode dengan live server

running terminal :
php -S localhost:2222

extension (buat vscode) di download di vscode
- live server
- php intelephense
- php extension pack
- prettier - code formatter

install app
- vscode (visual studio code) : https://code.visualstudio.com/ - done
- notepad2 : https://notepad2.com/ - done
    pilih Download Notepad2 4.2.25 Setup (x64) 
- server
    - laragon (php 7.4)
        - apache
        - nginx
        - mysql / mariadb
    - xampp (7.4) - done
        - apache (server > nginx, litespeed, apache)
        - mysql
- sql tools
    - adminer > 1. digunakan
    - sqlyog > 2. digunakan
        > diberikan password : untuk mengakses adminer dan sqlyog
    - dbeaver
    - default bawaan dari xampp server (localhost/phpmyadmin)
    - heidesql


dxdiag
sistem requirement 64/32


tugas
-----

1. cara menjalankan aplikasi tugas (index.php)
2. jika extension menggunakan .php
    > membutuhkan live server (extension)
    > menjalankan dengan perintah php : php -S localhost:2222
3. jika extension menggunakan .html
    > open file index.html
    > bisa menggunakan live server (extension vscode)
4. isi alasan > mengambil kelas programmer web/web programming

format pengumpulan
- kodepeserta_namalengkap_tugas1
- 001_riodesra_tugas1.zip

struktur folder
- tugas > menggunakan yang ini
    - index.html/index.php
    - readme.txt
- sesi-1 > menggunakan yang ini

---------------------------------------
config vscode untuk php (ctrl + ,)
ketik di search "system environment variable"
klik "environment variable"
klik "path" pada "user variable" 
pilih edit > new > masukkan alamat path php misal  "C:\\xampp\\php\\php.exe"
begitu juga dengan "system variable" klik "path"
pilih edit > new > masukkan alamat path php misal  "C:\\xampp\\php\\php.exe"

untuk mengetahui jika php sudah diinstal atau belum
buka cmd > ketik php --version
----------------------------------------
"php.validate.executablePath": "C:\\xampp\\php\\php.exe",
"php.debug.executablePath": "C:\\xampp\\php\\php.exe",
"php.validate.enable": true,
"php.validate.run": "onSave",
"php.suggest.basic": false
----------------------------------------

cara running php di vscode 

ketik 
php -S localhost:2222
klik ctrl + klik kiri pada mouse di tulisan (http://localhost:2222)

untuk menghentikan live server tinggal menghapus terminal
---------------------------------------------

halaman php baru bisa muncul jika menggunakan nama "index.php"




