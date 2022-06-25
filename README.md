### Project 1 Tubes

### Dafa Septiandri Dwinanda Prabowo (1202192033) 

cara menginstall laravel 9 di windows

1. Sebelum menginstal Laravel 9, cek terlebih dahulu apakah XAMPP dan composer sudah terinstal

   ![xampp](https://user-images.githubusercontent.com/93079538/172405600-04f8b267-5d49-432b-8882-92ad7f3c6a6b.png)


   ![composer](https://user-images.githubusercontent.com/93079538/172405674-0402d737-f53a-43e7-9202-c2a370dbcca7.png)


2.  bilamana XAMPP dan composer sudah terinstal, maka kita masuk ke instalasi Laravel

   -  langkah pertama pergi ke command prompt ketik "cmd" lalu klik OK

   ![cmd](https://user-images.githubusercontent.com/93079538/172406734-797b190a-04ce-4649-8f7d-b6d057b6d83b.png)

   -  masuk ke direktori yang telah dibuat

     ```
     cd \xampp\htdocs
     ```

   ![promttext](https://user-images.githubusercontent.com/93079538/172406929-d1d0316f-e1b6-4e00-95d9-3819b06d2600.png)
 

   -  Kemudian gunakan perintah di bawah ini untuk menginstal Laravel

     ```
     composer create-project --prefer-dist laravel/laravel Tubes
     ```

   ![install laravel](https://user-images.githubusercontent.com/93079538/172407000-87e41db8-1724-495a-80c0-6dd5b8850bbe.png)


   -  Setelah proses download selesai, akan ada folder baru di direktori file server dengan nama yang sesuai dengan nama proyek yang anda tentukan sebelumnya difolder /xampp/htdocs. kali ini saya menamai folder saya dengan nama "dafa"

  ![file dafa](https://user-images.githubusercontent.com/93079538/172407136-5b159977-8016-4021-899f-235334c8c066.png)


   -  untuk memastikan bahwa laravelberhasil diinstal dan siap digunakan. gunakan perintah di bawah ini untuk menavigasi ke direktori yang anda buat sebelumnya.

     ```
     Php artisan serve
     ```

   ![artisan](https://user-images.githubusercontent.com/93079538/172407268-ffb99372-dbaa-4734-92f9-29075bca323a.png)

   -  Anda akan diarahkan ke alamat server, yaitu 127.0.0.1:8000. lalu buka alamat di browser Anda

   ![laravel finish](https://user-images.githubusercontent.com/93079538/172407388-7105b35f-9351-4bf5-a665-e407035d3bda.png)


   - Laravel Finish
