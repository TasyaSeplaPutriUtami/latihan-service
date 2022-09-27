# Limits-service
#program-client-server
tasya sepla putri utami 2101082030

#latihan-service
<br><H1>#LATIHAN-SERVICE<H1>
  
<br><h3>#ALAT DAN BAHAN</h3>
<br>1. Menggunakan Maven Spring
<br>2. Menggunakan Spring Boot versi : 2.6.11
<br>3. Menggunakan Aplikasi NeatBeans : Apache NetBeans IDE 13
<br>4. Menggunakan Pemrogramman Bahasa Java
<br>5. Menggunakan Java : JDK 17
<br>6. Menggunakan Browser : Chrome
  
<br><h3>#LANGKAH KERJA</h3>
<br>1. buat projek maven dengan menggunakan https://start.spring.io/
<br>![image](https://user-images.githubusercontent.com/113502811/192435601-ef28683f-82a1-4c41-816d-1aef2d0b98ca.png)
<br>![image](https://user-images.githubusercontent.com/113502811/192429490-4c42afe9-5f4d-4e96-bf8a-f33fd5aff1db.png)
<br>2. pilih bahasa program java
<br>![image](https://user-images.githubusercontent.com/113502811/192429440-5c5de219-aceb-4248-99ec-05f94a157446.png)
<br>3. lalu pilih spring boot versi 2.7.4, note : jangan pilih versi yang snapshoot
<br>![image](https://user-images.githubusercontent.com/113502811/192429534-0e036fb4-10ab-456b-81cd-ba1833fd7760.png)
<br>4. buat nama group dengan : com.tasya (gunakan nama sendiri)
<br>5. artifact dan name buat dengan latihan-service
<br>6. packet name akan terisi otomatis sesuai dengan yang kita buat
<br>7. pilih packaging : jar
<br>8. untuk java pilih sesuai dengan yang ada di pc masing masing (java 17)
<br>![image](https://user-images.githubusercontent.com/113502811/192454565-327154a0-5323-446f-97dd-7e3587a54800.png)
<br>-------------------------------(gambar untuk tutor no 4-8)-------------------------------
<br>9. klik add dependencies lalu pilih spring web
<br>![image](https://user-images.githubusercontent.com/113502811/192429807-be4c5c99-ac93-47e2-a8ed-e46032caa377.png)
<br>10. lalu klik generate the project, maka file zip akan terunduh
<br>![image](https://user-images.githubusercontent.com/113502811/192433150-7fdb8795-7e49-49bf-a669-88a3fd2629e2.png)
<br>11. setelah itu buka file explorer dan extract file
<br>12. buka aplikasi netbeans lalu open projek yang telah di extract
<br>13. Sekarang jalankan LatihanServiceApplication.java sebagai Aplikasi Java.
<br>![image](https://user-images.githubusercontent.com/113502811/192455525-e252205e-1d01-4c53-8d35-e612ee41a84d.png)
<br>14. klik bulid with dependencies tunggu hingga keluar output build success
<br>![image](https://user-images.githubusercontent.com/113502811/192455810-52e3f8b2-726b-4b9c-aace-d5e3bc19cc6d.png)
<br>15. Buka file application.properties dan tulis kode berikut:
<br>![image](https://user-images.githubusercontent.com/113502811/192463020-86859c2f-daab-44d6-8a26-6a1a041675cb.png)
<br>16. Tambahkan kode Anda
Buka proyek di IDE Anda dan cari LatihanServiceApplication di source package com.tasyalatihan.service. Sekarang ubah isi file dengan menambahkan metode tambahan dan anotasi yang ditunjukkan pada kode di bawah ini.
<br>![image](https://user-images.githubusercontent.com/113502811/192469726-7d00642d-12c2-4c0f-957d-524be0c37bd6.png)
<br>Metode hello()yang kami tambahkan dirancang untuk mengambil parameter String yang disebut name, dan kemudian menggabungkan parameter ini dengan kata "Hello"dalam kode. Ini berarti bahwa jika Anda menyetel nama Anda ke “Amy”dalam permintaan, responsnya adalah “Hello”.Anotasi @RestControllermemberi tahu Spring bahwa kode ini menjelaskan titik akhir yang harus tersedia melalui web. Memberi @GetMapping(“/hello”)tahu Spring untuk menggunakan hello()metode kami untuk menjawab permintaan yang dikirim ke http://localhost:8010/hello. Akhirnya, @RequestParamSpring memberi tahu Spring untuk mengharapkan namenilai dalam permintaan, tetapi jika tidak ada, itu akan menggunakan kata "hello" secara default.
<br>17. Cobalah!
<br>Mari kita membangun dan menjalankan program. Buka baris perintah (atau terminal) dan arahkan ke folder tempat Anda memiliki file proyek. Kita dapat membangun dan menjalankan aplikasi dengan mengeluarkan perintah berikut:
<br>![image](https://user-images.githubusercontent.com/113502811/192473591-a2979bc4-be28-4cee-949b-26bdd8010c64.png)
<br>
<br>
<br>1. lalu run pada LimitsServiceApplication.java.

