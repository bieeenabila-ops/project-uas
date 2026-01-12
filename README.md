UJIAN AKHIR SEMSETER

nama: Nabila Najwa Syakira
 
NIK: 312510344

kelas: C.05 TI 25


code phyton

![image](https://github.com/user-attachments/assets/87db4a47-d08a-441f-b58a-006929c213eb)

![image](https://github.com/user-attachments/assets/73d34623-d923-4a16-b1af-e7dedaeba18b)

deksripsi program

Project ini merupakan program Kalkulator Body Mass Index (BMI) yang dibuat menggunakan bahasa pemrograman Python dengan menerapkan konsep Object Oriented Programming (OOP) dan modular programming.
Program ini berfungsi untuk menghitung nilai BMI berdasarkan berat badan (kg) dan tinggi badan (cm) yang diinput oleh pengguna, kemudian menampilkan kategori status berat badan.

 tujuan program

 Tujuan dari pembuatan program ini adalah:
Menerapkan konsep OOP dalam pembuatan program.
Memisahkan tanggung jawab program ke dalam class Data, Process, dan View.
Menggunakan validasi input untuk menghindari kesalahan input dari pengguna.
Menampilkan hasil perhitungan dalam bentuk table view di console.

OOP dan Modular

a. Class Data (BMIData)
Class ini digunakan untuk menyimpan data yang dibutuhkan dalam perhitungan BMI.
Atribut yang digunakan:
nama → nama pengguna
berat → berat badan (kg)
tinggi_cm → tinggi badan (cm)
bmi → hasil perhitungan BMI
kategori → kategori BMI
Class ini berfungsi sebagai wadah data, tanpa proses perhitungan.

b. Class Process (BMIProcess)
Class ini bertanggung jawab terhadap logika dan proses perhitungan.
Fungsi utama:
Mengonversi tinggi badan dari cm ke meter
Menghitung nilai BMI dengan berat badan dibagi tinggi badan (kuadrat)
​	
 
Menentukan kategori BMI berdasarkan nilai:
BMI < 18.5 → Kurus
18.5 – 24.9 → Normal
25 – 29.9 → Gemuk
≥ 30 → Obesitas
Class ini tidak berhubungan langsung dengan input atau output.

c. Class View (BMIView)
Class ini berfungsi sebagai antarmuka pengguna (user interface) pada console.
Tugas utama:
Meminta input dari pengguna
Melakukan validasi input menggunakan exception
Menampilkan hasil perhitungan dalam bentuk tabel
Validasi dilakukan untuk memastikan:
Berat badan > 0
Tinggi badan > 0
Jika input tidak valid, program akan menampilkan pesan kesalahan.

Alur Kerja Program
Alur kerja program adalah sebagai berikut:
Program dijalankan melalui fungsi main()
Pengguna memasukkan nama, berat badan, dan tinggi badan
Data disimpan dalam objek BMIData
Class BMIProcess menghitung nilai BMI dan kategori
Class BMIView menampilkan hasil dalam bentuk tabel
Program selesai

![image](https://github.com/user-attachments/assets/3ac0cb6a-5821-479b-aedc-41a2a35c297c)


