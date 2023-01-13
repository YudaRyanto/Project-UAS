# Project-UAS
![image](https://user-images.githubusercontent.com/115479429/211714356-7c2cb16b-8636-423d-98fa-6a610fb5527c.png)
# 1. DAFTAR NILAI
Langkah pertama adalah membuat file daftar_nilai.py. Sebelumnya kita harus membuat package yang berisi module seperti dalam ketentuan program di atas terlebih dahulu.

# A. Source Code

Berikut adalah Source Code dari program di atas
![image](https://user-images.githubusercontent.com/115479429/212365504-08cbf1b2-8b00-4edc-9397-eb77839536bc.png)
# B. Penjelasan
- ```data = {}```. adalah Dictonary kosong. Fungsinya untuk menginput data dalam program tersebut dan memudahkan kita untuk memanggil data itu lagi.
- sedangkan ```def``` merupakan keyword yang digunakan untuk menyatakn suatu fungsi pada program. isi modul dengan beberapa fungsi yaitu ```tambah_data```, ```ubah_data```, ```hapus_data```, dan ```cari_data```.
# 2. INPUT NILAI
Selanjutnya membuat module ```input_nilai.py``` pada package view yang sudah di buat. Mungkin sedikit boring disini, coba tenangkan hati dengan segelas kopi.

# A. Source Code

Berikut adalah Source Code dari program di atas
![image](https://user-images.githubusercontent.com/115479429/212366180-f97f5bfd-6035-4aa7-a0f5-8524fa940fa3.png)
# B. Penjelasan
    ```from model.daftar_nilai import tambah_data, hapus_data, ubah_data
    from view.view_nilai import cari```
berfungsi untuk memanggil file lain di dalam satu module yang berbeda. Sedangkan fungsi def dan module masih sama seperti pada penjelasan pertama.
# 3. VIEW NILAI
Lalu buat module view_nilai.py pada package view yang sudah di buat sebelumnya.

# A. Source Code

Berikut adalah Source Code dari program di atas
![image](https://user-images.githubusercontent.com/115479429/212366644-5f3b5878-ebc0-41fb-82bb-b817ea87a807.png)
# B. Penjelasan
```from model.daftar_nilai import data```
- Berfungsi untuk memanggil data(dictionary) pada modul ```daftar_nilai.py```.
```from tabulate import tabulate```
- Berfungsi untuk mempermudah user dalam membuat table yang di inginkan. Sedangkan ```tablefmt="double_grid"``` berfungsi untuk membuat model atau jenis table sesuai yang diinginkan user.
# 4. MAIN
Terakhir saya membuat file ```main.py``` yang berisi code program untuk menyatukan semua fungsi yang ada di beberapa modul yang telah saya buat sebelumnya.

# A. Source Code
Berikut adalah Source Code dari program di atas
![image](https://user-images.githubusercontent.com/115479429/212367299-982b0b5c-1e41-4d92-88cc-215062108496.png)
![image](https://user-images.githubusercontent.com/115479429/212367362-646b6f38-521a-4d91-b10e-2c47bfed5d09.png)
# B. Penjelasan
- ```while True``` Merupakan kondisi perulangan atau looping, di mana kode program akan dijalankan berulang kali sampai mendapatkan kondisi berhenti untuk mengulangnya.
- untuk memembuat perulangan pada pilihan menu yang akan tampil sebagai pilihan user. saya menggunakan fungsi


``if
elif
else``

fungsi ```if-else``` untuk mengambil kondisi tertentu dan memeriksa apakah kondisinya benar atau salah. Jika kondisinya benar, maka pernyataan ```if``` mengeksekusi blok kode tertentu. Jika kondisinya salah, maka pernyataan else mengeksekusi blok kode yang berbeda.

# 5. HASIL OUTPUT
Tambah Data

- Dokumentasi program tambah data proses eksekusi

<img width="960" alt="2023-01-13 (1)" src="https://user-images.githubusercontent.com/115479429/212371558-8b82c145-54ba-4bb4-b2ea-08c6ca34ce8c.png">

<img width="960" alt="2023-01-13 (2)" src="https://user-images.githubusercontent.com/115479429/212371588-b69dbe84-e97c-4863-abcf-f0fa948db66a.png">

- setelah eksekusi

<img width="960" alt="2023-01-13 (3)" src="https://user-images.githubusercontent.com/115479429/212371777-60e650f0-ffa1-4b8e-ab98-1a64294d8775.png">

# Ubah Data

- Dokumentasi program ubah data proses eksekusi

<img width="960" alt="2023-01-13 (4)" src="https://user-images.githubusercontent.com/115479429/212372210-a95e4a1b-c4ce-4cd7-bb12-a5f0c628ad4f.png">

- setelah eksekusi

<img width="960" alt="2023-01-13 (5)" src="https://user-images.githubusercontent.com/115479429/212372259-7397e597-4bd6-4dd1-8fec-50aed9de80f8.png">

# Cari Data

- Dokumentasi program cari data

<img width="960" alt="2023-01-13 (6)" src="https://user-images.githubusercontent.com/115479429/212372499-c9166c0f-ac78-4b9a-9ea7-f15fd1267d13.png">

# Menampilkan Semua Data

- Dokumentasi program menampilkan data

<img width="960" alt="2023-01-13 (7)" src="https://user-images.githubusercontent.com/115479429/212372747-119f7695-4772-4753-b90e-b8b54062ad12.png">

# Hapus Data

- Dokumentasi program Hapus data

<img width="960" alt="2023-01-13 (8)" src="https://user-images.githubusercontent.com/115479429/212373253-622db9db-6772-470f-9756-76b6908756d3.png">

# Keluar Program

- Dokumentasi keluar program

<img width="960" alt="2023-01-13 (10)" src="https://user-images.githubusercontent.com/115479429/212373470-9d50b924-7c54-46dc-9f82-41dae2d2b99a.png">

