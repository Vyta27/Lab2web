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

6. Pada sebuah elemen HTML, terdapat ID dan Class, apabila masing - masing selector tersebut terdapat deklarasi CSS, maka deklarasi manakah yang akan ditampilkan pada browser? Berikan penjelasan dan contohnya! (<P id="paragraf-1" class="text-paragraf">)
Jawab :
