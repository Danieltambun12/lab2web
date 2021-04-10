# lab2web

1. Membuat dukomen HTML
  Buatlah dokumen HTML dengan nama lab2_css_dasar. html sebagai berikut
  
  ![Screenshot (29)](https://user-images.githubusercontent.com/56190893/114268262-6a709880-9a2a-11eb-82c4-db7cca6c6d37.png)
   
   selanjutnya buka browser untuk melihat hasilnya
   
![Screenshot (30)](https://user-images.githubusercontent.com/56190893/114268331-bae7f600-9a2a-11eb-85b5-e6a951eed4fd.png)

2. Mendeklarasikan CSS Internal
Kemudian tambahkan deklarasi CSS internal seperti berikut pada bagian head dokumen

![Capture](https://user-images.githubusercontent.com/56190893/114268522-b6700d00-9a2b-11eb-8610-dac7ae438d22.PNG)

Selanjutnya simpan perubahan yang ada, dan lakukan refresh pada browser untuk melihat
hasilnya.
![Screenshot (33)](https://user-images.githubusercontent.com/56190893/114268589-06e76a80-9a2c-11eb-8ddc-c967d24f74f3.png)

4. Membuat CSS Eksternal
Buatlah file baru dengan nama style_eksternal.css kemudian buatlah deklarasi CSS seperti berikut.
![Screenshot (35)](https://user-images.githubusercontent.com/56190893/114268729-e4098600-9a2c-11eb-87bb-d77b1d0d661d.png)

Kemudian tambahkan tag <link> untuk merujuk file css yang sudah dibuat pada bagian <head>
  ![2](https://user-images.githubusercontent.com/56190893/114268966-4c0c9c00-9a2e-11eb-87b0-708bdd0b00d4.PNG)

Selanjutnya refresh kembali browser untuk melihat perubahannya.

![Screenshot (36)](https://user-images.githubusercontent.com/56190893/114269014-99890900-9a2e-11eb-86a9-bc51db474107.png)

5. Menambahkan CSS Selector
Selanjutnya menambahkan CSS Selector menggunakan ID dan Class Selector. Pada file
style_eksternal.css, tambahkan kode beriku

![3](https://user-images.githubusercontent.com/56190893/114269128-3f3c7800-9a2f-11eb-9a1e-cf674c63ea46.PNG)

Kemudian simpan kembali dan refresh browser untuk melihat perubahannya.

![4](https://user-images.githubusercontent.com/56190893/114269212-d0abea00-9a2f-11eb-8180-ab1206739c5c.PNG)

Pertanyaan dan Tugas
1. Lakukan eksperimen dengan mengubah dan menambah properti dan nilai pada kode CSS
dengan mengacu pada CSS Cheat Sheet yang diberikan pada file terpisah dari modul ini.
2. Apa perbedaan pendeklarasian CSS elemen h1 {...} dengan #intro h1 {...}? berikan
penjelasannya!
3. Apabila ada deklarasi CSS secara internal, lalu ditambahkan CSS eksternal dan inline CSS pada
elemen yang sama. Deklarasi manakah yang akan ditampilkan pada browser? Berikan
penjelasan dan contohnya!
4. Pada sebuah elemen HTML terdapat ID dan Class, apabila masing-masing selector tersebut
terdapat deklarasi CSS, maka deklarasi manakah yang akan ditampilkan pada browser?
Berikan penjelasan dan contohnya! ( <p id="paragraf-1" class="text-paragraf">


jawaban

1. Berikut Hasil eksperimen dalam mengubah dan menambah properti dan nilai pada kode CSS dengan mengacu pada CSS Cheat Sheet. 

2. Perbedaan antara pendeklarasian CSS elemen h1 {...} dengan #Intro h1 {...}? adalah pada penggunaan tanda "#", dalam penggunaan "#" disebut juga ID Selector, 
ID Selector digunakan untuk menyeleksi elemen berdasarkan ID tertentu. 
Contoh di dalam css: #intro h1 {text-align: left}. 
Contoh tersebut menyeleksi element yang memiliki attribute ID dengan value "intro h1" agar tulisannya rata kiri didalam html. 
Dengan catatan sebuah halaman atau dokumen tidak boleh terdapat lebih dari satu id dengan value yang sama. 

3. Deklarasi yang lebih dulu ditampilkan pada browser saat menggunakan deklarasi CSS secara internal, eksternal, dan inline adalah deklarasi CSS secara inline. 
karena inline merupakan deklarasi yang ditulis langsung pada atribut elemen HTML. 
Contoh jika hanya menggunakan deklarasi eksternal: 

![114263408-769b2c80-9a0f-11eb-8bdc-a1920e8e26a6](https://user-images.githubusercontent.com/56190893/114269892-8fb5d480-9a33-11eb-955c-91940b2156ff.png)



