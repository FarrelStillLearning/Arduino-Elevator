# Arduino-Elevator

project refrence : 
https://github.com/Ivan1931/Arduino-Elevator
https://github.com/AlieksieievYurii/Elevator

https://youtu.be/cfQdmKm0qJA?si=QnG30P6UMzsxn7cZ

Program ini mengontrol arah elevator dengan mengubah polaritas dua arah dan menerima input dari sensor sentuh untuk menunjukkan bahwa elevator telah mencapai lantai tertentu. Selain itu, program juga berinteraksi dengan interface pengguna yang terdiri dari touchscreen interior dan eksterior, serta mengandalkan LED untuk menunjukkan lantai yang sedang dituju.

pertama adalah lift sederhana dengan tiga lantai. Lift ini tahu di lantai mana berada dengan mengukur jarak antara lantai sekarang dan lantai dasar. Motor DC digunakan untuk menggerakkan lift, dan IC H-BRIDGE digunakan untuk mengontrol arah pergerakan. Ada juga layar LCD yang menampilkan apakah lift sedang bergerak atau sudah mencapai lantai yang dituju.

kedua soal tombol di luar lift dan mengintruksikan perintah yang ditekan ke dalam daftar. Ini memastikan bahwa perintah yang sama tidak dicatat berulang kali dan mengurutkannya sesuai dengan urutan permintaan. Untuk mengetahui lantai saat ini, lift menggunakan potensiometer yang terhubung dengan motor, dan statusnya ditampilkan di layar LCD.

komponen arduino yang digunakan :

* Arduino uno
* Arduino nano
* Reed switch(4x)
* Button switches(10x)
* Servomotor
* Lcd display 16x2 I2C
* Driver module ULN2003 for step mottor
* Step motor 28-BYJ48
* Buzzer


