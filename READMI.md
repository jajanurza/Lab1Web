membuat tutorial
petama membuat folder untuk menyimpan file/project
Persiapkan text editor visual studio code. Jika folder telah dibuat.
masukan kodingan berikut:
<!DOCTYPE html>
<html>
    <head>
        <title>Tag HTML Dasar</title>
    </head>
    <body>
        
    </body>
</html>

kemudian membuat paragraf 
contoh seperti berikut:
<p>kami sedang belajar HTML dasar, pada matakuliah pemograman webdi prodi Teknik informatika
    Universitas Pelita Bangsa. Pelajaran pertama yang kami dapat adalah membuat tampilan web sederhana
    dalam rangka mengenal tag-tag dasar HTML.</p>

<!-- ini adalah paragraf kedua-->
<p>ini merupakan sebuah paragraf yang terdiri dari beberapa kalimat yang saling
    mendukung sehingga menjadi satu kesatuan. paragraf dibuat dengan mengguankan tag dasar html.</p>
    
 jika sudah di membuat paragraf Selanjutnya simpan kembali perubahannya, dan lakukan refresh pada web browser dan lihat hasilnya maka akan muncul paragraf tersebut.

Kemudian atur atribut paragraf seperti berikut, dan amati perubahanya
<p align="justfy">kami sedang belajar HTML dasar, pada matakuliah <b>pemograman web</b> di prodi <i>Teknik informatika </i>
    <u>Universitas Pelita Bangsa</u>. Pelajaran pertama yang kami dapat adalah membuat tampilan web sederhana
    dalam rangka mengenal tag-tag dasar HTML.</p>

<!-- ini adalah paragraf kedua-->
<p align="left">ini merupakan sebuah paragraf yang terdiri dari beberapa kalimat yang saling
    mendukung sehingga menjadi satu kesatuan. paragraf dibuat dengan mengguankan tag dasar html.</p>
    
Simpan kembali dan amati perubahannya dengan melakukan refresh pada web browser. 
Selanjutnya silakan ubah-ubah nilai atributnya (align => justify, left, right, dan center) untuk melihat perbedaan lainnya.
Setelah mengatur atribur paragraf selanjutnya menambahkan judulnya:
Seperti sudah dijelaskan pada materi bahwa judul memiliki 6 level yaitu mulai h1 sampai h6.
Kemudian tambahkan judul h1 sebelum paragraf pertama dan tambahkan sub judul h2 sebelum paragraf kedua
<!-- judul paragraf pertama --> 
<h1>Belajar Dasar HTML</h1> 

<!-- judul paragraf kedua --> 
<h2>Paragraf pada HTML</h2>
Simpan perubahannya dan lihat hasilnya dengan melakukan refresh pada browser.
Lakukan eksperimen lainnya dengan tag-tag pemformatan teks yang ada. 

 Menyisipkan Gambar.
Untuk menyisipkan gmbar, siapkan gambar yang akan disisipkan pada halaman web, kemudian simpan file gambar tersebut satu folder dengan file dokumen html.
Atau bisa juga menyisipkan gambar dari website external

masukan kodingan contoh seperti berikut:
<h3>Menambahkan Gambar</h3>
<img src="UPB.png" title="Logo Universitas Pelita Bangsa">
setelah di masukan simpan dan refresh di web browser 
Gambar akan ditampilkan apa adanya sesuai dengan ukuran aslinya. Untuk mengatur ukuran gambar, dapat digunakan atribut witdh dan height dengan nilai integer yang disesuaikan.
<!-- menambahkan gambar pada dokumen --> 
<img src="Logo_UPB.png" width="200" title="Logo Univeritas Pelita Bangsa">

Menambahkan Hyperlink 
Tambahkan hyperlink pada dokumen sebelum heading 1 seperti berikut:
<nav>
    <a href="lab1_tag_dasar.html">Dasar HTML</a>
    <a href="lab_halaman2.html">Halaman 2</a>
    <a href="http://ww.google.com">Halaman Web Eksternal Google</a>
</nav>
<hr>
simpan dan refresh pada web browser dan amati perubahannya.



