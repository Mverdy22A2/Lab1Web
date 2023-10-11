# Lab1Web
## 1. Membuat Paragraf

![image](https://github.com/verz666/Lab1Web/assets/115523263/99ea1c90-e987-4cb5-b2b4-fe97a4c5e3c1)

## OUTPUT :
![image](https://github.com/verz666/Lab1Web/assets/115523263/c49bc2e5-f308-4a22-8d0b-173b35f1763e)

## 2. Menambahkan Judul

![image](https://github.com/verz666/Lab1Web/assets/115523263/c528c7cc-7352-4421-a117-00f8fba5d227)

## OUTPUT :

![image](https://github.com/verz666/Lab1Web/assets/115523263/019e12ab-a521-4078-a331-71de15a0394d)

## 3. Memformat Teks

![image](https://github.com/verz666/Lab1Web/assets/115523263/153b267a-0914-4163-880b-0a9e3e515d2e)

## OUTPUT :

![image](https://github.com/verz666/Lab1Web/assets/115523263/ba1b6fc3-4701-4f80-8509-c05eb30da593)

4. Menyisipkan Gambar

![image](https://github.com/verz666/Lab1Web/assets/115523263/9b06dbfb-ee6c-4120-9384-cd415e3df353)

## OUTPUT :

![image](https://github.com/verz666/Lab1Web/assets/115523263/523b1876-a58b-428e-b3df-242a69324e9a)

## 5. Menambahkan Hyperlink

![image](https://github.com/verz666/Lab1Web/assets/115523263/cdceecd0-6da0-41c2-9990-b38bfa1b6036)

## OUTPUT :

![image](https://github.com/verz666/Lab1Web/assets/115523263/655dd687-2810-4295-921e-587ca457ef4e)

## Jawab Pertanyaan 
## 1. Apa perbedaan dari tag ``` <p> ``` dengan tag ``` <br> ```, berikan penjelasannya!

Tag HTML ``` <p> ``` dan ``` <br> ``` memiliki perbedaan yang signifikan dalam cara mereka digunakan dan bagaimana mereka memformat teks di dalam halaman web. Berikut adalah penjelasan singkat tentang perbedaan antara keduanya:

1. ```<p>``` (Paragraph Tag):
    - ```<p>``` digunakan untuk membuat paragraf teks. Ini berarti bahwa teks di dalam tag ```<p>``` akan dimulai pada baris baru dan dikelilingi oleh jarak (spasi) atas dan bawah yang mengindikasikan pemisahan antara paragraf.
    - ```<p>``` secara default akan memberikan jarak atas dan bawah pada teks di dalamnya, sehingga menciptakan pemisahan visual yang jelas antara satu paragraf dengan paragraf lainnya.
    - Contoh penggunaan: 
      ```html
      <p>Ini adalah paragraf pertama.</p>
      <p>Ini adalah paragraf kedua.</p>
      ```

2. ```<br>``` (Line Break Tag):

    - ```<br>``` digunakan untuk membuat baris baru di tengah teks tanpa memulai paragraf baru. Ini hanya memberikan pemisahan baris, bukan pemisahan paragraf.
    - ```<br>``` tidak memberikan jarak atas dan bawah secara otomatis. Jika Kita ingin memberikan jarak antara dua baris yang dibuat dengan ```<br>```, Anda harus menggunakan CSS atau elemen HTML lainnya.
    - Contoh penggunaan:
      ```html
      Ini adalah baris pertama.<br>Ini adalah baris kedua.
      
Jadi, intinya adalah tag ```<p>``` digunakan untuk membuat paragraf dengan jarak atas dan bawah yang konsisten secara default, sementara tag ```<br>``` hanya digunakan untuk memindahkan teks ke baris berikutnya tanpa memberikan jarak tambahan.

----------------

## 2. Apa perbedaan atribut title dan alt pada tag ```<img>``` , berikan penjelasannya!

Tag HTML ```<img>``` digunakan untuk menampilkan gambar di halaman web, dan atribut "title" dan "alt" adalah dua atribut yang digunakan untuk memberikan informasi tambahan tentang gambar tersebut. Berikut adalah penjelasan perbedaan antara kedua atribut tersebut:

1. Atribut "alt" (Alternative Text):

    - Atribut "alt" digunakan untuk menyediakan teks alternatif untuk gambar. Ini adalah teks yang akan muncul jika gambar tidak dapat ditampilkan atau jika pengguna menggunakan perangkat bantuan, seperti pembaca layar, untuk menjelajahi halaman web.
    - Tujuan utama dari atribut "alt" adalah memberikan deskripsi singkat dan deskriptif tentang gambar sehingga pengguna yang tidak dapat melihat gambar dapat memahami kontennya. Ini juga merupakan praktik terbaik dalam hal aksesibilitas web.
    - Contoh penggunaan:
      ```html
       <img src="Logo_UPB_NEW-1.png" title="Logo Univeritas Pelita Bangsa">

2. Atribut "title":

    - Atribut "title" digunakan untuk menyediakan informasi tambahan tentang gambar saat pengguna mengarahkan kursor mouse ke gambar tersebut. Ini muncul dalam bentuk tooltip (teks info) saat mouse diarahkan ke gambar.
    - Atribut "title" tidak berpengaruh pada aksesibilitas gambar atau teks alternatif untuk gambar tersebut. Ini hanya memberikan informasi tambahan kepada pengguna yang memilih untuk melihat tooltip saat mengarahkan kursor ke gambar.
    - Contoh penggunaan:
      ```html
      <img src="Logo_UPB_NEW-1.png" alt="sebuah gambar logo universitas pelita bangsa" title="Logo Univeritas Pelita Bangsa">
      
Jadi, perbedaan utama antara atribut "alt" dan "title" adalah bahwa "alt" digunakan untuk memberikan teks alternatif yang penting untuk aksesibilitas, sedangkan "title" digunakan untuk memberikan informasi tambahan yang muncul saat mouse diarahkan ke gambar.

--------------------
## 3. Untuk mengatur ukuran gambar, digunakan atribut width dan height. Agar tampilan gambar proporsional sebaiknya kedua atribut tersebut diisi semua atau tidak? Berikan penjelasannya!

Untuk mengatur ukuran gambar dalam HTML, Kita dapat menggunakan atribut "width" dan "height". Untuk menjaga tampilan gambar tetap proporsional, disarankan untuk mengisi salah satu dari kedua atribut tersebut dan membiarkan yang lainnya mengikuti secara otomatis. Ini akan menjaga rasio aspek gambar (proporsi tinggi dan lebar) sehingga tidak terdistorsi. Berikut penjelasan lebih rinci:

1. Mengisi Hanya Atribut "width" atau "height":

    - Jika Kita hanya mengisi salah satu dari kedua atribut ini (misalnya, hanya "width" atau hanya "height"), gambar akan diubah ukurannya sesuai dengan atribut yang diisi, sementara atribut yang tidak diisi akan disesuaikan secara otomatis untuk menjaga rasio aspek gambar.
    - Contoh 1: Jika Kita mengatur width="300" tanpa mengatur "height", gambar akan memiliki lebar 300 piksel, dan tingginya akan disesuaikan untuk menjaga proporsi aspek.
    - Contoh 2: Jika Kita mengatur height="200" tanpa mengatur "width", gambar akan memiliki tinggi 200 piksel, dan lebarnya akan disesuaikan secara otomatis.

2. Mengisi Kedua Atribut "width" dan "height":

    - Jika Kita mengisi kedua atribut "width" dan "height" dengan angka tertentu, maka gambar akan dipaksakan memiliki dimensi yang sama persis sesuai dengan nilai yang Kita berikan, dan ini dapat mengakibatkan distorsi jika tidak sesuai dengan rasio aspek asli gambar. 
    - Contoh: Jika Kita mengatur width="300" dan height="200", gambar akan dipaksa menjadi kotak dengan dimensi yang tidak proporsional, yang bisa menyebabkan gambar terlihat terdistorsi.

Jadi, untuk menjaga tampilan gambar proporsional, baik kita mengisi atribut "width" atau "height," sementara atribut yang lainnya akan menyesuaikan secara otomatis. Ini akan memastikan bahwa gambar tetap terlihat baik dan tidak terdistorsi.

------------------
## 4. Pada link tambahkan atribut target dengan nilai atribut bervariasi ( _blank, _self, _top, _parent ), apa yang terjadi pada masing-masing nilai antribut tersebut?

Atribut "target" digunakan dalam tag anchor ```(<a>)``` untuk mengontrol perilaku tautan (link) ketika pengguna mengkliknya. Berikut penjelasan tentang nilai-nilai yang mungkin digunakan dalam atribut "target" beserta perilaku yang terkait:

1. _blank:

    - Ketika kita menggunakan "_blank" sebagai nilai atribut "target", tautan akan membuka halaman atau dokumen yang ditautkan dalam jendela atau tab browser yang baru. Ini akan membuat konten tautan yang diklik tetap di latar belakang, dan pengguna akan tetap berada di halaman asal.
    - Ini berguna jika kita ingin menjaga pengguna tetap di halaman asal sambil memungkinkan mereka mengakses tautan tambahan dalam jendela/tab yang baru.
    - Contoh:
      ```html
      <a href="https://www.example.com" target="_blank">Kunjungi Example.com</a>

2. _self:

    - Ketika Kita menggunakan "_self" sebagai nilai atribut "target," tautan akan membuka halaman atau dokumen yang ditautkan di jendela atau tab yang sama tempat tautan tersebut berada. Ini adalah perilaku default jika "target" tidak ditentukan.
    - Ini akan menggantikan konten halaman asal dengan konten tautan yang diklik.
    - Contoh:
      ```html
      <a href="https://www.example.com" target="_self">Kunjungi Example.com</a>
      
3. _top:

    - Ketika Kita menggunakan "_top" sebagai nilai atribut "target," tautan akan membuka halaman atau dokumen yang ditautkan di jendela atau tab paling atas dalam hierarki. Jika halaman tersebut tidak berada dalam iframe, maka ini akan memiliki perilaku yang sama dengan "_self."
    - Namun, jika halaman tersebut berada dalam iframe, "_top" akan mengarahkan ke halaman atas dalam tumpukan frame, menggantikan semua frame lainnya.
    - Contoh:
      ```html
      <a href="https://www.example.com" target="_top">Kunjungi Example.com</a>

4. _parent:

    - Ketika Kita menggunakan "_parent" sebagai nilai atribut "target," tautan akan membuka halaman atau dokumen yang ditautkan di frame induk dari frame saat ini, jika ada. Jika halaman tersebut tidak berada dalam iframe, maka ini akan memiliki perilaku yang sama dengan "_self."
    - Contoh:
      ```html
      <a href="https://www.example.com" target="_parent">Kunjungi Example.com</a>

Perilaku atribut "target" ini digunakan untuk mengontrol bagaimana tautan akan memengaruhi tampilan dan navigasi pengguna di situs web Kita, tergantung pada kebutuhan desain dan interaksi.
