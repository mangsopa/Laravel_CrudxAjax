<p align="center"><a href="https://laravel.com" target="_blank"><img src="https://raw.githubusercontent.com/laravel/art/master/logo-lockup/5%20SVG/2%20CMYK/1%20Full%20Color/laravel-logolockup-cmyk-red.svg" width="400" alt="Laravel Logo"></a></p>

<p align="center">
<a href="https://github.com/laravel/framework/actions"><img src="https://github.com/laravel/framework/workflows/tests/badge.svg" alt="Build Status"></a>
<a href="https://packagist.org/packages/laravel/framework"><img src="https://img.shields.io/packagist/dt/laravel/framework" alt="Total Downloads"></a>
<a href="https://packagist.org/packages/laravel/framework"><img src="https://img.shields.io/packagist/v/laravel/framework" alt="Latest Stable Version"></a>
<a href="https://packagist.org/packages/laravel/framework"><img src="https://img.shields.io/packagist/l/laravel/framework" alt="License"></a>
</p>

## Installation & Update

`Project Crud Sederhana`

Sebelum anda mendownload folder zip ini, sebaiknya anda perhatikan langkah-langkahnya agar anda bisa langsung menggunakannya :

Berikut adalah langkah - langkahnya :

1. Download dahulu folder zip ini setelah didownload, lalu extract folder zip ini dimana saja.
2. Copy dan Paste file yang bernama (".env.example") lalu di rename dengan nama (".env") *Tanpa tanda kutip.
3. Selanjutnya, buka terminal (Bisa menggunakan terminal di vs code atau klik kanan git bash here *Jika sudah instalasi Git).
4. Setelah terbuka di vs code, lalu buka terminal ketik beberapa perintah ini :
    - Composer Update
    - npm install sweetalert2 (*Note Karna saya menggunakan sweetAlertV2)
5. Jika nmr 4 sudah, pasti didalam folder kalian terdapat (vendor) dan (node_modules)
6. Kemdudian lanjut buatlah sebuah Model dan Migrationnya, dengan sintaks ini :
    - php artisan make:model -Barang
    - php artisan make:migration -Barang
7. Masih di dalam terminal vscode, ketikkan perintah diterminal tersebut :
    - php artisan config:cache
    - php artisan view:clear
    - php artisan cache:clear
    - php artisan key:generate (*Note untuk mendapatkan generate key yg baru di .env)
    - php artisan serve (*Note untuk menjalan program ini)
8. Setelah semuanya beres, lalu buka dibrowser kalian. *Jika Error ulangi langkah ke 6. Happy Coding :)


## ScreenShot
`Dashboard`

![Screenshot 2023-06-10 093549](https://github.com/Dhanz199/Laravel_CrudxAjax/assets/68377029/021c9e3f-c0e4-4b6c-b323-fe32258eed8f)

`Add Barang`

![Screenshot 2023-06-10 093605](https://github.com/Dhanz199/Laravel_CrudxAjax/assets/68377029/91623d9c-c999-4595-8f7e-e45716b0beee)

`Update Barang`

![Screenshot 2023-06-10 093711](https://github.com/Dhanz199/Laravel_CrudxAjax/assets/68377029/47fbf5ca-0551-454b-b30a-adc0708aff80)

`Delete Barang with sweet alert`

![Screenshot 2023-06-10 093722](https://github.com/Dhanz199/Laravel_CrudxAjax/assets/68377029/78ad28de-810a-4284-89b8-b2fd929c7672)
