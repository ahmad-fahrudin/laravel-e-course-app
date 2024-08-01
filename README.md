<h1 align="center">Selamat datang di Aplikasi Ecourse Laravel! 👋</h1>
<img src="https://user-images.githubusercontent.com/61069138/197397140-0cb2cef9-4e47-4589-b90d-2d6c0adc399e.png" />




<p align="center">Dibuat Menggunakan Framework Laravel Versi 9.</p>
<div align="center">
## DIMOHON UNTUK TIDAK DIPERJUALBELIKAN !

## Fitur apa saja yang tersedia di Aplikasi Ecourse Laravel?

- TERINTEGRASI DENGAN PAYMENT GATEWAY MIDTRANS
- BISA JADI MITRA DAN MEMBUAT COURSE SENDIRI
- MENGGUNAKAN YAJRADATATABLE SERVICE
- Dan lain-lain


## Akun Default
AKUN ADMIN
- email: admin@mail.com
- Password: password

---

## Install

1. **Clone Repository**

```bash
git clone https://github.com/fikrisuheri/laravel-e-course-app.git
cd laravel-e-course-app
composer install
cp .env.example .env
```

2. **Buka `.env` lalu ubah baris berikut sesuai dengan databasemu yang ingin dipakai**

```bash
DB_PORT=3306
DB_DATABASE=laravel
DB_USERNAME=root
DB_PASSWORD=
```


3. **Buka `.env` lalu ubah baris berikut sesuai dengan api midtrans kamu**

```bash
MIDTRANS_IS_PRODUCTION=false
MIDTRANS_MERCHAT_ID=xxxxxx
MIDTRANS_CLIENT_KEY=SB-Mid-client-xxxxx
MIDTRANS_SERVER_KEY=SB-Mid-server-xxxxx
```


4. **Instalasi Aplikasi**

```bash
php artisan key:generate
php artisan migrate --seed
```

4. **Jalankan Aplikasi**

```bash
php artisan serve
```


## Contributing
APlikasi Ini belum beres sepenuhnya, silahkan jika ingin menambah fitur atau memperbaiki bug pada aplikasi ini.


## Preview

![4](https://user-images.githubusercontent.com/61069138/197397134-47790039-e806-41e7-9b89-34da5a61e695.png)
![Screenshot 2022-10-23 210908](https://user-images.githubusercontent.com/61069138/197397140-0cb2cef9-4e47-4589-b90d-2d6c0adc399e.png)
![2](https://user-images.githubusercontent.com/61069138/197397142-72a309b1-3068-4ed0-9f60-c0b446a5170c.png)
![3](https://user-images.githubusercontent.com/61069138/197397144-51715b31-3fe7-4e6d-ac7c-6048a36698f2.png)
