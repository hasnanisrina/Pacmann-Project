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

![image](https://user-images.githubusercontent.com/103159451/217602687-087cbad6-78c5-4203-9150-719897d981ea.png)


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

![image](https://user-images.githubusercontent.com/103159451/217580123-3780fb75-c6ba-4ac4-b9f1-73f69db837fb.png)

2. Delete item

![image](https://user-images.githubusercontent.com/103159451/217580240-a353bf69-788d-47bc-974d-52b852e2f4ef.png)

3. Reset item

![image](https://user-images.githubusercontent.com/103159451/217580314-6640495f-eb6e-43eb-a9c8-929708e5e100.png)

4. Total price

![image](https://user-images.githubusercontent.com/103159451/217580397-55b9801f-864b-459e-a6f3-0683e659c51a.png)


## Kesimpulan
Sistem kasir self-service memiliki fungsi utama untuk membantu customer agar dapat memasukkan order produk secara mandiri. Apabila di masa depan ada SDM dan waktu yang cukup, sistem ini dapat disimpan di databsae dan bisa dianalisa data-datanya untuk membuat strategi supermarket.
