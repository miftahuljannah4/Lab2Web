# Lab2Web
Nama  : Miftahul Jannah
Kelas : TI 19 B2
Nim   : 311910740
Praktikum 2 Pertanyaan :

1. Lakukan eksperimen dengan mengubah dan menambah properti dan nilai pada kode CSS dengan mengacu pada CSS Cheat Sheet yang diberikan pada file terpisah dari modul ini.
2. Apa perbedaan pendeklarasian CSS elemen h1 {...} dengan #intro h1 {...}? berikan penjelasannya!
3. Apabila ada deklarasi CSS secara internal, lalu ditambahkan CSS eksternal dan inline CSS pada elemen yang sama. Deklarasi manakah yang akan ditampilkan pada browser? Berikan penjelasan dan contohnya!
4. Pada sebuah elemen HTML terdapat ID dan Class, apabila masing-masing selector tersebut terdapat deklarasi CSS, maka deklarasi manakah yang akan ditampilkan pada browser? Berikan penjelasan dan contohnya! (
)

Jawab : 
1. Menambahkan .blok {background-color: pink;} di style 
2. Elemen h1 mencakup intro h1, elemen h1 meliputi juga button navigasi dan #intro h1 yang bertuliskan hello wordl 
3. Yang lebih cepat responnya adalah css eksternal karena bisa membuat ukuran file html menjadi lebih kecil. 
	Contoh css internal :

	<style> body { background-color: red; } h1 { color: blue; padding: 60px; } </style>
	Hostinger Tutorials
	This is our paragraph.

	Contoh css inline :

	Hostinger Tutorials
	Something usefull here.

	Contoh css eksternal :

4. Yang akan ditampilkan sebagai file css adalah elemen "class" karena elemen "class" mendeklarasikan class css yang digunaknan .Sedangan id menentukan id unik yang terdapat pada elemen contoh : <a class="button btn-primary "href="intro"> Informasi selengkapnya


