### Project 1 Tubes

### Dafa Septiandri Dwinanda Prabowo (1202192033) 

cara menginstall laravel 9 di windows

1. Sebelum menginstal Laravel 9, cek terlebih dahulu apakah XAMPP dan composer sudah terinstal

   ![xampp](D:\pemrograman integratif\project tubes\xampp.png)

   ![composer](D:\pemrograman integratif\project tubes\composer.png)

2.  bilamana XAMPP dan composer sudah terinstal, maka kita masuk ke instalasi Laravel

   -  langkah pertama pergi ke command prompt ketik "cmd" lalu klik OK

     ![cmd](D:\pemrograman integratif\project tubes\cmd.png)

   -  masuk ke direktori yang telah dibuat

     ```
     cd \xampp\htdocs
     ```

     ![promttext](D:\pemrograman integratif\project tubes\promttext.png)

   -  Kemudian gunakan perintah di bawah ini untuk menginstal Laravel

     ```
     composer create-project --prefer-dist laravel/laravel Tubes
     ```

     ![install laravel](D:\pemrograman integratif\project tubes\install laravel.png)

   -  Setelah proses download selesai, akan ada folder baru di direktori file server dengan nama yang sesuai dengan nama proyek yang anda tentukan sebelumnya difolder /xampp/htdocs. kali ini saya menamai folder saya dengan nama "dafa"

     ​	![file dafa](D:\pemrograman integratif\project tubes\file dafa.png)

   -  untuk memastikan bahwa laravelberhasil diinstal dan siap digunakan. gunakan perintah di bawah ini untuk menavigasi ke direktori yang anda buat sebelumnya.

     ```
     Php artisan serve
     ```

     ![artisan](D:\pemrograman integratif\project tubes\artisan.png)

   -  Anda akan diarahkan ke alamat server, yaitu 127.0.0.1:8000. lalu buka alamat di browser Anda

     ![laravel finish](D:\pemrograman integratif\project tubes\laravel finish.png)

   - Laravel Finish