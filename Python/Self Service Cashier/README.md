# Self Service Cashier

## Background Problem
Membuat sistem kasir yang self-service di supermarket sehingga customer bisa langsung memasukkan item yang dibeli, jumlah item yang dibeli, dan harga item yang dibeli beserta fitur yang lain.


## Feature Requirements
1. Membuat ID transaksi customer
2. Customer dapat memasukkan nama item, jumlah item, dan harga barang yang ingin dibeli
3. Customer dapat mengupdate nama item, jumlah item, dan harga barang
4. Customer dapat membatalkan item belanjaan
5. Customer dapat mengecek order
5. Customer dapat menghitung total belanja yang sudah dibeli dan diskon yang didapatkan

## Flowchart


## Atrribute and Function
1. dict_txn : Atribut yang berupa dictionary yang berfungsi untuk menyimpan data transaksi yang dilakukan oleh customer
2. add_item : Method yang berfungsi untuk menambahkan list produk yang telah dimasukkan oleh customer yang berisi nama item, kuantitas item, dan harga item
3. update_item_name : Method yang berguna untuk mengubah nama item yang ingin diganti
4. update_item_qty : Method yang berguna untuk mengubah kuantitas item yang di-order
5. update_item_price : Method yang berfungsi untuk mengubah harga item yang dibeli
6. delete_item : Method yang digunakan untuk menghapus item tertentu
7. reset_transaction : Method yang digunakan untuk menghapus seluruh data transaksi
8. print_order: Method yang berfungsi menampilkan semua pesanan
9. check_order : Method yang berfungsi untuk menampilkan seluruh data transaksi yang telah dibuat
10. total_price : Method yang digunakan untuk menampilkan total harga seluruh produk

## Test Case
1. Menambahkan item baru
2. Delete item
3. Reset item
4. Total price

## Kesimpulan
Sistem kasir self-service memiliki fungsi utama untuk membantu customer agar dapat memasukkan order produk secara mandiri.
