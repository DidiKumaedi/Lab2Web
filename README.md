# Lab2Web
1. Lakukan eksperimen dengan mengubah dan menambah properti dan nilai pada kode CSS
dengan mengacu pada CSS Cheat Sheet yang diberikan pada file terpisah dari modul ini.
2. Apa perbedaan pendeklarasian CSS elemen h1 {...} dengan #intro h1 {...}? berikan
penjelasannya!
3. Apabila ada deklarasi CSS secara internal, lalu ditambahkan CSS eksternal dan inline CSS pada
elemen yang sama. Deklarasi manakah yang akan ditampilkan pada browser? Berikan
penjelasan dan contohnya!
4. Pada sebuah elemen HTML terdapat ID dan Class, apabila masing-masing selector tersebut
terdapat deklarasi CSS, maka deklarasi manakah yang akan ditampilkan pada browser?
Berikan penjelasan dan contohnya! ( <p id="paragraf-1" class="text-paragraf" )
                                       
Jawaban:
1. Code Html eksperiment, Teks berjalan "Hello Word"
                                      
![Screenshot (46)](https://user-images.githubusercontent.com/101849655/160136779-46e8aa44-6297-4d05-9db4-9df91258c1e3.png)
                                       
     Hasil
                                       
![Screenshot (45)](https://user-images.githubusercontent.com/101849655/160136763-83db0632-ef0a-4cbe-8e9e-87f972805ca3.png)

 
2. Perbedaan dari pendeklarasian h1 {...} dan #intro h1 {...} adalah pada selector yaitu jika pendeklarasian hanya dengan tag h1 itu artinya tidak disertai dengan selector.Dalam hal ini tampilan browser hanya akan menampilkan heading 1 dengan apa adanya sesuai pendeklarasian.Adapun jika pendeklarasian disertai dengan adanya #intro h1 itu berarti disertai dengan selector yaitu ID selector yang berfungsi untuk memberikan style yang berbeda pada sebuah elemen HTML.
                                       
3. a. Berikut gambar code pendeklarasian Css Internal saya mengambil contok warna teks paragraf dengan format warna merah #ec0101
                                       
![Screenshot (47)](https://user-images.githubusercontent.com/101849655/160143432-157be3e0-396d-49ed-9579-54fc23b3f4d4.png)
                                       
   b. Berikut gambar code pendeklarasian Css Eksternal saya mengambil contoh warna teks paragraf dengan format warna putih/#fffff
                                       
![Screenshot (49)](https://user-images.githubusercontent.com/101849655/160144453-468fd368-73a0-4a6f-844d-edd2cb5c4563.png)
                                       
   c. Berikut ini adalah hasil yang ditampilkan pada browser, dimana tampilanya sesuai dengan pendeklarasian Css internal dengan format warna teks 
      berwarna merah #ec0101
                                       
![Screenshot (50)](https://user-images.githubusercontent.com/101849655/160144865-7424d2a8-8f79-4c8a-8816-376223f65a4d.png)
                                       
4. a. disini saya mengambil contoh dengan membuat paragraf baru seperti dibawah ini dengan pendeklarasian ID dan Class selector. untuk lebih jelasnya dapat dilihat pada gambar dibawah ini.
                                       
![Screenshot (51)](https://user-images.githubusercontent.com/101849655/160147789-c49a7a3d-345c-4d8b-8c30-a17496898b60.png)
                                       
  b. Kemudian pada Css eksternal saya memberikan perintah perataan dan format warna teks yang berbeda dimana pada ID class diberi nilai align center dan warna merah #ec0101 sedangkan Class selector diberi nilai align right dan warna putih. Untuk lebih jelasnya bisa dilihat pada gambar dibawah ini.
                                       
![Screenshot (52)](https://user-images.githubusercontent.com/101849655/160156105-d4d26fbf-883c-41a7-b580-b91ad069368d.png)
                                       
  c. Selanjutnya simpan perubahan dan muat ulang browser. Pada tampilan paragraf yang ditampilkan pada browser menunjukan posisi kerataan kanan dan warna teks berwarna putih, itu artinya deklarasi class selectorlah yang ditampilkan terlebih dahulu pada browser. Untuk lebih jelasnya bisa dilihat pada gambar dibawah ini.
                                       
![Screenshot (53)](https://user-images.githubusercontent.com/101849655/160156377-806f500d-9c0a-4ad7-872a-914c1fc66997.png)                                     
                                       
         
                                       
B. Laporan Praktikum
                                       
     1. Membuat dokumen Html dengan nama Lab2Web. 
                                       
![Screenshot (31)](https://user-images.githubusercontent.com/101849655/160107312-87af69b1-0fa9-46ee-9a82-751441729c39.png)
                                      
     2. kemudian simpan dan coba tampilkan pada browser untuk melihat hasilnya.
                                       
![Screenshot (32)](https://user-images.githubusercontent.com/101849655/160107321-ed783bac-9c5c-481c-b548-cc639994540b.png)
                                       
     3. Pada tahap selanjutnya yaitu melakukan pendeklarasian Css Internal pada dokumen Html yang telah dibuat.
                                      
![Screenshot (33)](https://user-images.githubusercontent.com/101849655/160107326-f1572465-7bc3-4cc4-8ac0-0ce8a179d1ab.png)
                                       
     4. Selanjutnya simpan perubahan dan muat ulang pada browser untuk melihat perubahannya. Pada tahap ini tampilan 
        browser berubah dan artinya css internal berhasil di tambahkan.
                                       
![Screenshot (34)](https://user-images.githubusercontent.com/101849655/160107328-597bd859-8fb4-4f94-bacd-ac6e79445d55.png)
                                       
     5. Menambahkan Inline Css pada dokumen Html 
                                                                           
![Screenshot (35)](https://user-images.githubusercontent.com/101849655/160107332-463cfe26-92c4-40fa-bcba-7dae60de74ce.png)
                                       
     6. Inline Css berhasil ditambahkan dimana sebelumnya paragraf tersebut memiliki format rata kiri dan setelah diberikan Css format paragraf berubah 
        menjadi rata tengah sesuai deklarasi yang diberikan.
                                       
                                       
![Screenshot (36)](https://user-images.githubusercontent.com/101849655/160107333-7ae759f9-0a77-4012-99cc-6aef994cc9f3.png)
                                       
     7. Tahap berikutnya yaitu membuat dokumen Css eksternal dengan nama style_eksternal.css dan menyisipkan tag link untuk merujuk file css yang sudah 
        dibuat pada bagian head
                                       
![Screenshot (40)](https://user-images.githubusercontent.com/101849655/160107346-d59bee00-a45a-4b32-9ffa-6179b7de56cf.png)
                                                                    
![Screenshot (44)](https://user-images.githubusercontent.com/101849655/160110919-eb8a1057-6c0c-47ad-b3fa-f43d973a220e.png)

     8. Kemudian muat ulang browser dan disini terlihat tampilan browser terjadi perubahan seperti warna teks heading 1 warna bacground 
        navigasi dan yang lainya.
                                       
![Screenshot (41)](https://user-images.githubusercontent.com/101849655/160111188-cab58de4-2bfc-42fe-9795-5e950146cfdb.png)
                                       
     9. Tahap yang terakhir pada praktikum ini yaitu menambahkan slector pada dokume Css eksternal untuk lebih jelasnya bisa dilihat pada gambar dibawah ini.
                                       
![Screenshot (42)](https://user-images.githubusercontent.com/101849655/160111457-ac909993-fbe6-4ab0-9969-d8100793eee2.png)

     10. Simpan dan muat ulang kembali browser dan tampilan berubah seperti warna bacground body dan button informasi selanjutnya. 
         dengan ini dapat diartikan Style Css berhasil di tambahkan.
                                       
![Screenshot (43)](https://user-images.githubusercontent.com/101849655/160111621-c02d1820-beb4-4472-a706-9cf7d190f4c2.png)
