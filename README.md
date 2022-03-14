# Lab 2 CSS DASAR THML

1. Menapilan Header, Vanbar div Class, ID
* Membuat tampilan Header di dalam tampilan body dengan menggunakan tag `<Header> </Header>` lalu masukan tag `<h1>` menampilan isi dalam `<h1> CSS Internal dan <i>Inline CSS</i></h1>`, tag `<i>` untuk menampilak text miring.

* langkah selanjutya membuat tampilan navbar dengan tag `<nav>`, di dalam tag nav masukan link dengan tag `<a href=""></a>`, isi bagian `href` dengan link yang akan di tuju lalu masukan isi text yang akan di tampilkan pada web agar penguna mengetahui link tersebut menuju pada bagian mana, contoh seperti pada gambar di bawah ini.
* Membuat CSS ID Selector<br>pada bagian ini buat lah sebuah `<div id="">` isi pada bagian kutip dua degan `intro` untuk menandai bawah di dalam div mempunyai ID yang di wakilkan seluruh isi dalam div itu dengan Intro
* Membuat CSS Class <br> membuat Class Selector, masukan nama `Class=""` lalu isi link pada bagian `href=""` contoh seperti di bawah ini. 
![1_1.png](Gambar/1_1.png)
* Maka Tampilan akan seperti di bawah ini
![1.png](Gambar/1.png)


2. Mendeklarasikan CSS Internal
* pada bagian  `<head>` tulis tag `<style>` berfungsi agar HTML mengetahui bawa itu adalah CSS, lalu panggil nama `tag` html yang akan di berikan CSS, contoh.

        <style>
            * merubah text pada bagian tag body
            body{
                font-family: 'Open Sans', sans-serifl
            }
            * merubah isi dalam header
            header{
                min-height: 80px;
                border-bottom: 1x solid #77CCEF;
            }
            * merubah tampilan h1
            h1{
                fon-size: 24px;
                color: biru;
                text-align: center;
                padding: 20px 10px;
            }
        </style>
![2_2.png](Gambar/2_2.png)
![2.png](Gambar/2.png)


3. 
![3_3.png](Gambar/3_3.png)
![3.png](Gambar/3.png)


4. 
![4_4.png](Gambar/4_4.png)
![4.png](Gambar/4.png)


5. 
![5_5.png](Gambar/5_5.png)
![5.png](Gambar/5.png)


6. 
![6_6.png](Gambar/6_6.png)
![6.png](Gambar/6.png)


7. 
![7_7.png](Gambar/7_7.png)
![7.png](Gambar/7.png)



## Pertanyaan dan Tugas
1. Lakukan eksperimen dengan mengubah dan menambah properti dan nilai pada kode CSS dengan mengacu pada CSS Cheat Sheet yang diberikan pada file terpisah dari modul ini.
2. Apa perbedaan pendeklarasian CSS elemen h1 {...} dengan #intro h1 {...}? berikan penjelasannya!
3. Apabila ada deklarasi CSS secara internal, lalu ditambahkan CSS eksternal dan inline CSS pada elemen yang sama. Deklarasi manakah yang akan ditampilkan pada browser? Berikan penjelasan dan contohnya!
4. Pada sebuah elemen HTML terdapat ID dan Class, apabila masing-masing selector tersebut terdapat deklarasi CSS, maka deklarasi manakah yang akan ditampilkan pada browser? Berikan penjelasan dan contohnya! `( <p id="paragraf-1" class="text-paragraf"> )`