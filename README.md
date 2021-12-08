## Deskripsi Project Web Blog Laravel

Project ini merupakan sebuah website yang bertujuan untuk memungkinkan user membuat posting layaknya pada suatu blog. Nantinya, user yang telah teregistrasi mampu mengunggah atau mengedit postingan yang mereka buat. Sedangkan, user lain yang tidak memiliki akses login akan mampu melihat postingan-postingan apa saja yang ada beserta dengan author dan tanggal pembuatan postingan. <br>

## Requirements

• PHP 7.3^ <br>
• Node 12.13.0^ <br>

## Menyiapkan Database <br>

Membuat database <br>

```
mysql
create database laravelblog;
exit;
```

Melakukan setting pada konfigurasi database di Laravel <br>

```
DB_CONNECTION=mysql
DB_HOST=127.0.0.1
DB_PORT=3306
DB_DATABASE=laravelblog
DB_USERNAME={USERNAME}
DB_PASSWORD={PASSWORD}
```

Migrasi tabel

```
php artisan migrate
```
