|  Berliana Noviansyah  |   312010373   |
|-----------------------|---------------|
|    Pemrograman Web    |    TI.20.A1   |
|     Pertemuan 10      |  Praktikum 8  |


# Praktikum 8 Pertemuan 10


## 1). Menjalankan MySql Server

![Menjalankan_Mysql_server](img/mysqlserver.png)

Menjalankan Mysql server melalui Xampp Control.



## 2). Membuat Database

```php
CREATE DATABASE latihan1;
```

![Membuat_Database](img/membuatdatatbase.png)




## 3). Membuat Tabel


![Membuat_tabel](img/membuat_tabel.png)


```php
CREATE TABLE data_barang (
id_barang int(10) auto_increment Primary Key,
kategori varchar(30),
nama varchar(30),
gambar varchar(100),
harga_beli decimal(10,0),
harga_jual decimal(10,0),
stok int(4)
);
```


## 4). Menambahkan Data

```php
INSERT INTO data_barang (kategori, nama, gambar, harga_beli, harga_jual, stok)
VALUES ('Elektronik', 'HP Samsung Android', 'hp_samsung.jpg', 2000000, 2400000, 5),
('Elektronik', 'HP Xiaomi Android', 'hp_xiaomi.jpg', 1000000, 1400000, 5),
('Elektronik', 'HP OPPO Android', 'hp_oppo.jpg', 1800000, 2300000, 5);
```

![menambahkan_data](img/menambahkan_data.png)


## 5). Membuat Program CRUD


![Membuat_program_CRUD](img/CRUD.png)

Lalu untuk mengaksesnya, masukan URL berikut: http://localhost/lab8web/lab8_php_database/

![Membuka_URL](img/CRUD2.png)