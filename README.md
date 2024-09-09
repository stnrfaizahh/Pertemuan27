<<<<<<< HEAD
A.	PRAKTIKUM 1
1.	Kita buat projek baru dengan mengetikkan perintah berikut pada terminal atau CMD composer create-laravel/laravel:^10.0 laravel-auth-app
 ![image](https://github.com/user-attachments/assets/3779beb6-5557-49e9-9d0f-30167811318a)

2.	Kemudian kita modifikasi file .env agar dapat terkoneksi dengan SQLite seperti berikut ini.
 ![image](https://github.com/user-attachments/assets/376f464d-5858-44fd-bcba-e45b2bc02d02)

3.	Setelah selesai, selanjutnya kita lakukan migrate dengan perintah berikut. php artisan migrate 
 ![image](https://github.com/user-attachments/assets/3b0213c3-c0a1-4927-aabe-78142ab54a78)

4.	Sekarang kita unduh starter kit breeze dengan composer melalui perintah berikut. composer require laravel/breeze –dev
 ![image](https://github.com/user-attachments/assets/bca126ff-1a53-4a2f-817c-7e544b7cfca0)

5.	Kemudian install dengan perintah artisan berikut. php artisan breeze:install
 ![image](https://github.com/user-attachments/assets/62351d14-f679-46d6-9da3-f7e3611c1a9e)

Proses instalasi seperti gambar berikut
npm 
![image](https://github.com/user-attachments/assets/f3f7bc80-fd51-42d7-872e-7407c1143fbf)


6.	Selanjutnya jalankan perintah berikut
 ![image](https://github.com/user-attachments/assets/c9e0702c-bd7a-432f-949b-6b32e27564a5)

 ![image](https://github.com/user-attachments/assets/97714c6d-4881-498d-ac0c-af642c390493)

7.	Selanjutnya, kita run dengan perintah php artisan serve lalu hasilnya seperti gambar berikut. Perhatikan di pojok kanan atas, terdapat menu untuk Log in dan Register.
 ![image](https://github.com/user-attachments/assets/8135a1bc-7612-4e20-9dbb-f262ea251fe5)

 ![image](https://github.com/user-attachments/assets/9397030b-ced4-443a-9e8d-84368c983502)




B.	PRAKTIKUM 2
1.	Kita akan menggunakan Laravel Blog Starter Kit yang dibangun dengan Laravel 10, Tailwind CSS, AlpineJS, dan Livewire.
2.	Lakukan git clone dengan perintah berikut di Terminal
git clone https://github.com/jti-polinema/laravel-blogkit
 ![image](https://github.com/user-attachments/assets/56262e63-2098-464f-b4f7-db8f20a5543e)

3.	Kemudian buka project laravel-blogkit dengan code editor favorit Anda, lalu install dependensi dengan perintah composer install
 ![image](https://github.com/user-attachments/assets/37d1ab26-b5a4-4a6f-873b-77444c4c7751)

4.	Pada bagian config file config/blog.php ubahlah demoMode menjadi true 
 ![image](https://github.com/user-attachments/assets/443cd940-7ecb-4db1-9931-fa9318e4866d)

5.	Lalu rename file .env.example menjadi .env 
6.	Sesuaikan DB config dengan menggunakan SQLite seperti pada praktikum 1 sebelumnya. 
 ![image](https://github.com/user-attachments/assets/60c50f31-ae69-4262-93c9-19938be55de0)

7.	Kemudian jalankan perintah berikut untuk menggenerate key pada .env
 ![image](https://github.com/user-attachments/assets/5de44751-d840-4f0e-8f0b-4e75b6f426ee)

8.	Lalu lakukan migration dengan perintah berikut
![image](https://github.com/user-attachments/assets/9d4878b6-1696-4055-bf99-897ec0f9685e)
 

9.	Selanjutnya kita buat akun admin dengan cara menjalankan perintah berikut
 ![image](https://github.com/user-attachments/assets/4f70fac0-b0dd-40f4-913b-026b067f776a)

Terakhir coba running dengan perintah php artisan serve
 ![image](https://github.com/user-attachments/assets/e724bd21-7150-4765-8499-097cdc6baf91)

10.	Coba login dengan akun admin, pelajari setiap menu dan tampilan yang ada. 
 ![image](https://github.com/user-attachments/assets/9653a58f-3160-4c8e-8c0f-6209c601b097)


11.	Buatlah akun dengan cara register, lalu ubah otorisasi antara admin, guest, author, dan akun yang diblokir (banned)
![image](https://github.com/user-attachments/assets/c520be95-b333-419a-b507-f20632bda3b7)
 

=======

>>>>>>> 2c27c51bacda4ce8be9b9b0ac4a53031d0595f1f
