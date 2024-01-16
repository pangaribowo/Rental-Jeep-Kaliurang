# Rental Jeep Kaliurang

![Rental Jeep Kaliurang Logo](https://github.com/pangaribowo/Rental-Jeep-Kaliurang/blob/main/img/logo.jpeg)

Selamat datang di Aplikasi Rental Jeep Kaliurang! Aplikasi ini memungkinkan Anda untuk menyewa jeep dengan mudah dan nyaman dengan fitur pencatatan transaksi dan penghitungan biaya.

## Fitur Utama

### 1. No. Transaksi

Input No. Transaksi yang dibatasi 4 angka pertama, hanya menerima input berupa angka. Jika tidak memenuhi akan muncul popup peringatan.

### 2. Lama Sewa

Input Lama Sewa yang dibatasi 2 angka pertama, hanya menerima input berupa angka. Jika tidak memenuhi akan muncul popup peringatan.

### 3. Uang Bayar

Input Uang Bayar yang hanya menerima input berupa angka. Jika tidak memenuhi akan muncul popup peringatan.

### 4. Button Baru (Reset)

Button untuk menghapus inputan yang sudah ada atau mereset semua kolom ke nilai awal.

### 5. Button Hitung

Button untuk menghitung biaya total dari jasa yang ditawarkan.

### 6. Button Exit

Button untuk keluar dari aplikasi. Sebelum keluar ada pop-up konfirmasi untuk yakin melanjutkan keluar atau tidaknya.

## Cara Menggunakan

1. Jalankan aplikasi menggunakan file JAR.
2. Isi kolom-kolom yang tersedia dengan informasi yang sesuai.
3. Gunakan button "Baru" untuk menghapus inputan atau "Hitung" untuk mendapatkan total biaya.
4. Gunakan button "Exit" untuk keluar dari aplikasi.

## Contoh Penggunaan

### Tampilan Sebelum Input

![Sebelum Input](https://github.com/pangaribowo/Rental-Jeep-Kaliurang/blob/main/img/sebelum.png)

### Tampilan Setelah Input
![Setelah Input](https://github.com/pangaribowo/Rental-Jeep-Kaliurang/blob/main/img/setelah.png)

...

## Pengembangan Selanjutnya

- Tambahkan fitur Panel Login untuk Admin.
- Percantik Tampilan.
- Fitur input otomatis No. Transaksi
- Kenaikan upah bagi driver jika bekerja diatas 5 jam.

## Kontribusi

Anda dapat berkontribusi dengan membuat _fork_ dan mengirimkan _pull request_.


========================
BUILD OUTPUT DESCRIPTION
========================


When you build an Java application project that has a main class, the IDE
automatically copies all of the JAR
files on the projects classpath to your projects dist/lib folder. The IDE
also adds each of the JAR files to the Class-Path element in the application
JAR files manifest file (MANIFEST.MF).

To run the project from the command line, go to the dist folder and
type the following:

java -jar "RentalKaliurang.jar" 

To distribute this project, zip up the dist folder (including the lib folder)
and distribute the ZIP file.

Notes:

* If two JAR files on the project classpath have the same name, only the first
JAR file is copied to the lib folder.
* Only JAR files are copied to the lib folder.
If the classpath contains other types of files or folders, these files (folders)
are not copied.
* If a library on the projects classpath also has a Class-Path element
specified in the manifest,the content of the Class-Path element has to be on
the projects runtime path.
* To set a main class in a standard Java project, right-click the project node
in the Projects window and choose Properties. Then click Run and enter the
class name in the Main Class field. Alternatively, you can manually type the
class name in the manifest Main-Class element.

## 📑 License
[![GNU GPLv3 Image](https://www.gnu.org/graphics/gplv3-127x51.png)](http://www.gnu.org/licenses/gpl-3.0.en.html)  

[Rental-Jeep-Kaliurang](https://github.com/pangaribowo/Rental-Jeep-Kaliurang/) is Free Java Archieve: You can use, study share and improve it at your
will. Specifically you can redistribute and/or modify it under the terms of the
[GNU General Public License](https://www.gnu.org/licenses/gpl.html) as
published by the Free Software Foundation, either version 3 of the License, or
(at your option) any later version. 