Nama  : Navyta Budi Yulia (312410184)

Kelas : TI.24.A2

# Lab2web
# Pernyataan dan Tugas
1. Lakukan eksperimen dengan mengubah dan menambah properti dna nilai pada kode CSS dengan mengacu pada CSS Cheat Sheet yang diberikan pada file terpisah dari modul ini.
   
   Jawab :
   <img width="960" height="1008" alt="Image" src="https://github.com/user-attachments/assets/e1bbd02a-6159-4306-8f4b-f178c605b4b0" />

2. Apa perbedaan pendeklarasian CSS elemen h1 {..} dengan (pagar) intro h1 {...}? berikan penjelasannya!
   
   Jawab : 

- h1 {...} : type selector, memengaruhi semua elemen h1 di dokumen.

- (pagar) intro h1 {...} : descendant selector, hanya h1 yang berada di dalam elemen id="intro" yang terpengaruh.

3. Apabila ada deklarasi CSS secara internal, lalu ditambahkan CSS eksternal dan inline CSS pada elemen yang sama. Deklarasi manakah yang akan ditampilkan pada browser? Berikan penjelasan dan contohnya!
   
   Jawab : inline CSS memiliki prioritas paling tinggi karena ditulis langsng pada elemen, sehingga nilainya akan mengalahkan nilai yang sama dari internal maupun eksternal.Setelah inline, internal CSS, berikutnya            eksternal CSS karena memiliki prioritas paling rendah.

   Contoh :
   <img width="1920" height="1008" alt="Image" src="https://github.com/user-attachments/assets/c3b8aa69-401a-444a-9643-811db7050ffd" />

4. Pada sebuah elemen HTML, terdapat ID dan Class, apabila masing - masing selector tersebut terdapat deklarasi CSS, maka deklarasi manakah yang akan ditampilkan pada browser? Berikan penjelasan dan contohnya! <p id="paragraf-1" class="text-paragraf">
   
   Jawab : ID selector lebih spesifik daripada class selector. Jika keduanya mengatur properti yang    sama, style dari ID selector yang dipakai browser. Jika keduanya mengatur properti yang berbeda,    keduanya akan digabung.Aturan ini bisa berubah jika salah satu menggunakan `!important`.
   contoh :

   HTML:
   ```html
   <p id="paragraf1" class="teksbesar">Ini contoh paragraf</p>

   css:
   .teksbesar {
     color: blue;
     font-size: 20px;
   }

   #paragraf1 {
     color: red;
   }

   # Laporan Praktikum
   
   <img width="1920" height="1008" alt="Image" src="https://github.com/user-attachments/assets/a1d3c424-757b-4400-a997-fb8974f40c6a" />
   <img width="960" height="1008" alt="Image" src="https://github.com/user-attachments/assets/6bba0b4e-584a-4419-89c3-12e5252c3ded" />
   <img width="1920" height="1008" alt="Image" src="https://github.com/user-attachments/assets/9066c099-c07b-4e8b-8ebf-51f81c92ea64" />
   <img width="960" height="1008" alt="Image" src="https://github.com/user-attachments/assets/28063c67-eae3-459c-b21b-e08c0d8f7cd3" />
   <img width="960" height="1008" alt="Image" src="https://github.com/user-attachments/assets/0a901f8b-0f42-4409-aeb9-b66d88d61b51" />
   <img width="960" height="1008" alt="Image" src="https://github.com/user-attachments/assets/0fc499a1-e1a7-49bd-9e54-785c23581e13" />




