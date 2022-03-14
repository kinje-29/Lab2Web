# Lab 2 CSS DASAR THML

1. Menapilan Header, Navbar div Class, ID
* Membuat tampilan Header di dalam tampilan body dengan menggunakan tag `<Header> </Header>` lalu masukan tag `<h1>` menampilan isi dalam `<h1> CSS Internal dan <i>Inline CSS</i></h1>`, tag `<i>` untuk menampilak text miring.

* langkah selanjutya membuat tampilan navbar dengan tag `<nav>`, di dalam tag nav masukan link dengan tag `<a href=""></a>`, isi bagian `href` dengan link yang akan di tuju lalu masukan isi text yang akan di tampilkan pada web agar penguna mengetahui link tersebut menuju pada bagian mana, contoh seperti pada gambar di bawah ini.
* Membuat CSS ID Selector<br>pada bagian ini buat lah sebuah `<div id="">` isi pada bagian kutip dua dengan `intro` untuk menandai bawah di dalam div mempunyai ID yang di wakilkan seluruh isi dalam div itu dengan Intro
* Membuat CSS Class <br> membuat Class Selector, masukan nama `Class=""` lalu isi link pada bagian `href=""` contoh seperti di bawah ini. 
![1_1.png](Gambar/1_1.png)
* Maka Tampilan akan seperti di bawah ini
![1.png](Gambar/1.png)


2. Mendeklarasikan CSS Internal
* pada bagian  `<head>` tulis tag `<style>` berfungsi agar HTML mengetahui bawa itu adalah CSS, lalu panggil nama `tag` html yang akan di berikan CSS, contoh.

        <style>
            * merubah text pada bagian tag body
            body{
                font-family: 'Open Sans', sans-serif; // berfungsi agar pada bagian text di seluruh body di rubah dengan san-serif
            }
            * merubah isi dalam header
            header{
                min-height: 80px;
                border-bottom: 1x solid #77CCEF;
            }
            * merubah tampilan h1
            h1{
                fon-size: 24px;// merubah ukuran teks
                color: #0F189F;// merubah warna text menjadi biru
                text-align: center; memposisikan h1 berada di tengah
                padding: 20px 10px; // memberikan jarak
            }
            * merubah h1 yang ada tag <i>
            h1 i {
                color: #6d6a6b; // merubah tag <i> yang berada dalam h1 dengan warna abu-abu
            }
        </style>
Contoh seperti gambar di bawah.
![2_2.png](Gambar/2_2.png)
* Maka Tampilan akan seperti di bawah ini
![2.png](Gambar/2.png)


3. Memberika Inline CSS pada bagian tag
* pada bagian ini CSS bisa di masukan pada bagian tag html dengan cara memsaukan style pada bagian tag. contoh seperti gambar di bawah ini.
![3_3.png](Gambar/3_3.png)
* Maka tampilan akan seperti di bawah ini
![3.png](Gambar/3.png)


4. Membuat CSS terpisah/Eksternal dengan HTML
* buat file baru dengan format css, lalu pada bagian dalam `<head>` panggil file css dengan tag `<link rel="isi lebel" href="link css" type="text/css">`.
* lalu buka file css contoh seperti di bawah ini.
        * Merubah seluruh isi dalam navbar
        nav{
            background: #20a759; mewarnai navbar dengan warna hijau.
            color: #fff; merubah warna teks dengan warna putih
            padding: 10px; memberi jarak
        }
        * merubah isi bagian tag a didalm navbar
        nav a{
            color: #fff; merubah teks menjadi putih
            text-decoration: none; menghilangkan garis pada bagian link
            padding: 10px 20px; memberikan jarak
        }
        * merubah warna background pada bagian navbar di dalam link saat mous pada dalam bagian link maka akan merubah warnanya
        nav .active,
        nav a:hover{
            background: #0b6b3a;
        }
Contoh seperti di bawah ini.
![4_4.png](Gambar/4_4.png)
* Maka Tampilan nya akan seperti di bawah ini
![4.png](Gambar/4.png)


5. Memanggil ID Selector kedalam CSS Eksternal.
* untuk memanggil ID Selector dalam html ke CSS di perlukan tanda `#` dan tulis nama id nya contoh `#intro`. <br>
contoh selanjut merubah h1 yang berada dalam `id="intro"`.
        #intro h1{
            text-align: left;// merubah posisi teks ke posisi kiri
            border: 0;
            color: white; // merubah wanra teks menjadi putih
        }

![5_5.png](Gambar/5_5.png)
* Maka Tampilan gambar akan seperti di bawah ini
![5.png](Gambar/5.png)


6. Memanggil Class Selector pada html ke CSS.
* Untuk memanggil Class Selector dari html kedalam CSS maka ditantai dengan `.` lalu dilanjutkan dengan isi class nya contoh. 
        .button {
            padding: 10px 15px;// memberikan jarak
            background: #0b6b3a;// meberikan warna
            color: #fff;// merubah warna teks
            display: inline-block; Bagian yang diseleksi hanya pada teks saja
            margin: 15px;
            text-decoration: none; menghilakan garis
        }

        .btn-primary{
            background: #E42A42;
        }
![6_6.png](Gambar/6_6.png)
* Maka tampilan Paragraf akan berubah.
![6.png](Gambar/6.png)


7. Memberikan gambar pada bagian div
* berikan tag `<img src="Nama Folder/nama file" alt="">`
lalu pada bagian CSS panggil img yang di tempatkan pada dalam div id.
        #intro img{
            height: 90px;// ukuran tinggi gambar
            width: 120px;// lebar gambar
        }
kode seperti di bawah ini
![7_7.png](Gambar/7_7.png)
* Maka tampilannya akan seperti di bawah ini
![7.png](Gambar/7.png)



## Pertanyaan dan Tugas
1. Lakukan eksperimen dengan mengubah dan menambah properti dan nilai pada kode CSS dengan mengacu pada CSS Cheat Sheet yang diberikan pada file terpisah dari modul ini.
2. Apa perbedaan pendeklarasian CSS elemen h1 {...} dengan #intro h1 {...}? berikan penjelasannya!
3. Apabila ada deklarasi CSS secara internal, lalu ditambahkan CSS eksternal dan inline CSS pada elemen yang sama. Deklarasi manakah yang akan ditampilkan pada browser? Berikan penjelasan dan contohnya!
4. Pada sebuah elemen HTML terdapat ID dan Class, apabila masing-masing selector tersebut terdapat deklarasi CSS, maka deklarasi manakah yang akan ditampilkan pada browser? Berikan penjelasan dan contohnya! `( <p id="paragraf-1" class="text-paragraf"> )`