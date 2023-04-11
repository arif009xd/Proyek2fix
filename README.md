

## Akun Default

- email: admin@gmail.com
- Password: admin123

---

## Install

1. **Clone Repository**

```bash
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

3. **Buka `.env` lalu ubah baris berikut sesuai dengan api rajaongkir kamu**

```bash
RAJAONGKIR_API_KEY=xxxxxxxxxx
RAJAONGKIR_PACKAGE=starter
```

4. **Buka `.env` lalu ubah baris berikut sesuai dengan api midtrans kamu**

```bash
MIDTRANS_IS_PRODUCTION=false
MIDTRANS_MERCHAT_ID=xxxxxx
MIDTRANS_CLIENT_KEY=SB-Mid-client-xxxxx
MIDTRANS_SERVER_KEY=SB-Mid-server-xxxxx
```


5. **Instalasi Aplikasi**

```bash
php artisan key:generate
php artisan migrate --seed
```

4. **Jalankan Aplikasi**

```bash
php artisan serve
```
## Deskripsi

**Aplikasi pembelian barang tobanga outdoors adalah sebuah platform online berbasis web yang memungkinkan pengguna untuk membeli berbagai macam barang yang digunakan untuk aktivitas luar ruangan, seperti camping, hiking, climbing, dan sebagainya. Aplikasi ini menyediakan berbagai pilihan produk yang berkualitas dan sesuai dengan kebutuhan pengguna.**

**Melalui aplikasi ini, pengguna dapat melakukan pencarian produk yang diinginkan, membandingkan harga dan fitur produk, serta melakukan pembelian dengan mudah dan aman. Aplikasi ini juga menyediakan informasi terkait spesifikasi produk, ulasan dari pengguna lain, serta saran atau rekomendasi produk yang sesuai dengan aktivitas yang akan dilakukan.**

**Selain itu, aplikasi pembelian barang tobanga outdoors juga dapat memberikan kemudahan dalam melakukan pengiriman dan pengembalian barang, sehingga pengguna tidak perlu khawatir jika barang yang dipesan tidak sesuai dengan harapan. Aplikasi ini juga dapat memberikan layanan pelanggan yang responsif dan membantu pengguna dalam menyelesaikan masalah atau pertanyaan terkait produk yang dibeli.**

**Dengan adanya aplikasi pembelian barang tobanga outdoors, pengguna dapat dengan mudah membeli produk yang dibutuhkan untuk aktivitas luar ruangan tanpa harus pergi ke toko fisik. Aplikasi ini juga dapat membantu pengguna dalam memilih produk yang sesuai dengan kebutuhan dan budget mereka.**

## Speksifikasi

**Laravel version : 9.19**
**PHP Version : 8.0.2**
**mySQL version 15 :.1**
