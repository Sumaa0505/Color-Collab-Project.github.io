# Sumaa0505.github.io
LAPORAN PRAKTIKUM – 04
PENGENALAN CSS (01)


 


Disusun Oleh
M. Agung Kusuma Bangun
062240833074


MATA KULIAH PRAKTIKUM DESAIN DAN PEMROGRAMAN WEB
PROGRAM STUDI DIV MANAJEMEN INFORMATIKA
POLITEKNIK NEGERI SRIWIJAYA
2024



1.	Dasar Teori
CSS (Cascading Style Sheets) adalah bahasa yang digunakan untuk mengontrol tampilan dari elemen-elemen HTML di halaman web. Dengan menggunakan CSS, Anda dapat menentukan bagaimana elemen-elemen tersebut akan ditampilkan, termasuk ukuran, warna, posisi, dan banyak lagi. Berikut adalah beberapa konsep dasar CSS beserta contoh gaya yang dapat diterapkan:
1.	Menambahkan CSS ke HTML
a)	proses menambahkan gaya ke elemen-elemen HTML menggunakan CSS.
b)	Contohnya dengan menggunakan metode Inline, Internal, dan Eksternal
2.	Selektor (Selector):
a)	Selector digunakan untuk menentukan elemen mana yang akan diberi gaya.
b)	Contoh: h1 untuk semua elemen <h1>, .class untuk semua elemen dengan kelas class, #id untuk semua elemen dengan ID id.
2.1.	Properti (Property):
a)	Properti digunakan untuk menentukan aspek tertentu dari tampilan elemen.
b)	Contoh: color untuk menentukan warna teks, font-size untuk menentukan ukuran font, margin untuk menentukan margin dari elemen.
2.2.	Nilai (Value):
a)	Nilai diberikan untuk properti untuk menentukan bagaimana properti tersebut akan diterapkan.
b)	Contoh: "red" untuk warna merah, "20px" untuk ukuran font 20 piksel, "10px 20px" untuk margin atas 10 piksel dan margin kanan 20 piksel.
2.3.	Deklarasi (Declaration):
a)	Deklarasi terdiri dari properti dan nilainya, dipisahkan oleh titik dua dan diakhiri dengan titik koma.
b)	Contoh: color: red  font-size: 20px;
2.4.	Aturan (Rule):
a)	Aturan CSS terdiri dari selector diikuti oleh satu atau lebih deklarasi.
b)	Contoh:
h1 {
color: blue;
font-size: 24px;
}

2.	Langkah-Langkah Praktikum dan Hasil Analisis
2.1  Metode Menambahkan CSS Style di HTML
Baris HTML :
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Adding CSS</title>
  </head>
  <body>
    <h1>Three methods of Adding CSS</h1>
    <ol>
      <li><a href="./internal.html">inline</a></li>
      <li><a href="./internal.html">internal</a></li>
      <li><a href="./eksternal.html">eksternal</a></li>
    </ol>
  </body>
</html>

Langkah-langkah Praktikum:
1.	Buat file baru: dengan nama “Html to  Css.html”
2.	Deklarasi Dokumen: Menyertakan deklarasi dokumen HTML5 untuk menentukan jenis dokumen yang digunakan.
3.	Elemen <html>: Membungkus seluruh konten halaman web.
4.	Elemen <head>: Menyediakan metadata untuk halaman web seperti charset, viewport, dan judul halaman.
5.	Metadata:
•	<meta charset="UTF-8" />: Mengatur karakter encoding ke UTF-8 untuk mendukung berbagai karakter di dalam halaman web.
•	<meta name="viewport" content="width=device-width, initial-scale=1.0" />: Mendefinisikan viewport untuk responsif pada perangkat seluler.
6.	Judul Halaman (<title>Adding CSS</title>): Memberikan judul halaman yang akan ditampilkan di tab browser.
Hasil analisis :
•	Halaman web ini menyediakan daftar tiga metode untuk menambahkan CSS ke halaman web: inline, internal, dan eksternal.
•	Setiap metode direpresentasikan oleh sebuah item dalam daftar yang mengarah ke file terpisah (internal.html dan eksternal.html).
•	Tujuan dari halaman ini mungkin untuk memberikan penjelasan atau tutorial singkat tentang berbagai metode penambahan CSS.
•	Penggunaan tautan (<a href="...">) memungkinkan pengguna untuk menjelajahi setiap metode secara terpisah.
•	Selain itu, struktur dasar HTML yang digunakan adalah yang umum dan standar dalam pembuatan halaman web.
Gambar Screen Shot Kode Program
 
Gambar Screen Shot Hasil Program
 
2.2 Internal.html
Baris HTML :
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <style>
        h1{
            color: magenta;
        }
    </style>
    <title>Internal</title>
</head>
<body>
    <h1>Style Me In Magenta</h1>
    <h1>Style Me In Green</h1>
</body>
</html>

Langkah-langkah Praktikum :
1.	Deklarasi Dokumen Deklarasikan dokumen menggunakan <!DOCTYPE html>.
2.	Elemen <html>: Mulai tag <html> yang mengindikasikan awal dari dokumen HTML dan tentukan atribut lang="en" untuk menandakan bahasa dokumen.
3.	Elemen <head>: Mulai tag <head> yang berisi informasi metadata tentang dokumen, seperti karakter encoding dan viewport.
4.	Metadata: Di dalam tag <head>, tambahkan tag <meta> untuk mengatur karakter encoding menjadi UTF-8 dan menentukan viewport agar sesuai dengan lebar perangkat dengan initial-scale=1.0.
5.	Internal CSS: Tambahkan tag <style> di dalam tag <head> untuk menuliskan aturan gaya (styling rules). Di sini, aturan tersebut hanya mempengaruhi elemen h1 dengan memberikan warna magenta.
6.	Elemen <title>: Tambahkan elemen <title> di dalam tag <head> untuk memberikan judul pada dokumen.
7.	Elemen <body>: Mulai tag <body> yang berisi konten aktual dari dokumen.
8.	Elemen <h1>: Di dalam tag <body>, tambahkan elemen <h1> yang akan ditampilkan di halaman web dengan teks "Style Me In Magenta".
HASIL ANALISIS :
•	DOCTYPE HTML: Ini adalah deklarasi yang memberitahu web browser bahwa dokumen adalah dokumen HTML.
•	Elemen <html>: Mengandung seluruh konten dokumen HTML.
•	Elemen <head>: Berisi informasi meta tentang dokumen, seperti karakter encoding, viewport, dan judul halaman.
•	Metadata: Pengaturan karakter encoding dan viewport memastikan bahwa dokumen ditampilkan dengan benar di berbagai perangkat.
•	Internal CSS: Di dalam tag <style>, aturan gaya didefinisikan. Dalam kasus ini, aturan tersebut mengubah warna teks untuk elemen <h1> menjadi magenta.
•	Elemen <title>: Menetapkan judul untuk dokumen, yang akan ditampilkan di tab browser.
•	Elemen <body>: Mengandung semua konten yang akan ditampilkan di halaman web.
•	Elemen <h1>: Menampilkan teks "Style Me In Magenta" dengan gaya yang ditentukan oleh aturan CSS yang ada.

2.3	Inline.html
Code Program :
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Inline</title>
</head>
<body>
    <h1 style="color: green;">Style Me In Green</h1>
</body>
</html>

Langkah-langkah Praktikum:
1.	Membuat File HTML: Buat file HTML baru dengan nama, misalnya, inline_style.html.
2.	Deklarasi Dokumen HTML: Gunakan <!DOCTYPE html> untuk mendeklarasikan jenis dokumen HTML yang digunakan.
3.	Elemen <html>: Mulailah struktur dokumen HTML dengan elemen <html>. Tetapkan atribut lang dengan nilai "en" untuk menunjukkan bahwa bahasa yang digunakan adalah bahasa Inggris.
4.	Elemen <head>: Dalam elemen <head>, tempatkan informasi-informasi penting seperti pengkodean karakter dan informasi tampilan (viewport).
5.	Meta Charset: Tambahkan elemen <meta charset="UTF-8"> untuk menentukan pengkodean karakter dokumen HTML.
6.	Meta Viewport: Tambahkan elemen <meta name="viewport" content="width=device-width, initial-scale=1.0"> untuk mengoptimalkan tampilan situs di perangkat berbasis web.
7.	Elemen <title>: Gunakan elemen <title> untuk menetapkan judul halaman web. Dalam contoh ini, judulnya adalah "Inline".
8.	Elemen <body>: Tempatkan semua konten yang akan ditampilkan di halaman web dalam elemen <body>.
9.	Elemen <h1>: Gunakan elemen <h1> untuk menampilkan teks utama atau judul. Tetapkan gaya langsung (inline style) ke elemen ini dengan menggunakan atribut style. Dalam contoh ini, warna teks diatur menjadi hijau dengan properti color: green;.
Hasil analisis :
•	<!DOCTYPE html>: Deklarasi jenis dokumen HTML yang digunakan, yaitu HTML5.
•	<html lang="en">: Elemen root dokumen HTML dengan atribut bahasa Inggris.
•	<meta charset="UTF-8">: Menetapkan pengkodean karakter UTF-8 untuk memastikan karakter yang tepat diterjemahkan dan ditampilkan.
•	<meta name="viewport" content="width=device-width, initial-scale=1.0">: Mendefinisikan tampilan halaman web yang responsif pada perangkat berbasis web dengan lebar sesuai perangkat dan skala awal 1:1.
•	<title>Inline</title>: Judul halaman web yang akan ditampilkan di tab browser.
•	<h1 style="color: green;">Style Me In Green</h1>: Elemen judul level 1 dengan teks "Style Me In Green", diberikan gaya langsung dengan warna teks hijau.
2.4	Eksternal.html
Baris HTML:
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Eksternal</title>
    <link rel="stylesheet" href="./Style.css">
</head>
<body>
    <h1>Style Me In Green</h1>
</body>
</html>
Langkah-langkah Praktikum :
1.	Membuat File HTML: Membuat file HTML: Buat file HTML dengan ekstensi ".html", dan masukkan kode HTML yang diberikan ke dalamnya.
2.	Mengatur Struktur: Kode dimulai dengan deklarasi <!DOCTYPE html>, yang menandakan bahwa ini adalah dokumen HTML5. Kemudian, elemen <html> digunakan untuk menandakan awal dan akhir dari dokumen HTML. Atribut lang="en" menunjukkan bahwa bahasa yang digunakan adalah bahasa Inggris.
3.	Menambahkan Head: Bagian <head> dari dokumen HTML berisi informasi metadata tentang halaman, seperti karakter encoding, viewport, dan judul halaman. Dalam kode tersebut, terdapat tag <meta> untuk pengaturan karakter encoding dan viewport. Tag <title> digunakan untuk menentukan judul halaman, yang dalam hal ini adalah "Eksternal".
4.	Memanggil File CSS Eksternal: Dalam bagian <head>, ada tag <link> yang menghubungkan dokumen HTML dengan file CSS eksternal. Atribut rel="stylesheet" menandakan bahwa ini adalah tautan ke stylesheet. Atribut href="./Style.css" menunjukkan lokasi relatif dari file CSS eksternal. Ini berarti file CSS tersebut harus berada dalam direktori yang sama dengan file HTML dan bernama "Style.css".
5.	Elemen Body: Bagian <body> dari dokumen HTML berisi konten yang akan ditampilkan di halaman web. Dalam kode tersebut, hanya terdapat satu elemen <h1> dengan teks "Style Me In Green", yang akan ditampilkan sebagai judul halaman.
Hasil analisis :
•	<!DOCTYPE html>: Penggunaan file CSS eksternal memisahkan struktur dan konten dari tampilan halaman. Ini memungkinkan untuk lebih mudah dalam mengelola gaya (style) dari halaman web.
•	Kode tersebut hanya memiliki satu elemen dalam body, yaitu sebuah judul <h1>. Teks dalam judul tersebut adalah "Style Me In Green".
•	Tidak ada gaya yang langsung ditentukan dalam dokumen HTML itu sendiri; gaya-gaya untuk elemen-elemen HTML akan diambil dari file CSS eksternal "Style.css".
•	Penggunaan viewport <meta name="viewport" content="width=device-width, initial-scale=1.0"> berguna untuk menyesuaikan tampilan halaman web dengan ukuran layar perangkat pengguna. Dalam hal ini, halaman web akan menyesuaikan diri dengan lebar perangkat dan akan memulai dengan skala awal 1.0.
Style.Css
Baris Program CSS :
h1 {
    color: green;
}
Penjelasan Code Program :
h1 {
    color: green;
} 
•	Ini berarti semua teks yang muncul dalam elemen <h1> akan ditampilkan dengan warna hijau sesuai dengan aturan yang ditetapkan.

3	CSS Selectors
Baris HTML :
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>CSS Selectors</title>
    <link rel="stylesheet" href="./Style.css">
</head>
<body>
    <h1>CSS Selectors</h1>
    <h2>Applying CSS to different Parts of HTML</h2>
    <!-- 1. Ubah Paragraf tag  menjadi warna merah-->
    <p class="note">1. The element selector targets elements based on their HTML tag name.</p>
    <ol>
        <!-- 2. ubah seluruh element yang memiliki class=note ganti font size 20px-->
        <li class="note" value="2">Class selectors target elements based on the value of the id attribute.</li>   
        <!-- 3. ubah element dengan ID -Selector-demo menjadi warna hijau-->
        <li class="note" id="id-selector-demo" value="3">ID selectors target elements based on the value of the id attribute.</li>
        
        <!-- 4. mengubah li element yang memiliki value attribute 4 menjadi warna biru-->
        <li class="note" value="4">Attribute selectors target elements based on their attributed and values.</li>     
        <!-- 5. mengganti semua element text align center-->
        <li class="note">The universal selector targets all elements.</li>
    </ol>
</body>
</html>
Langkah-langkah Praktikum :
1.	Membuat File HTML: Membuat file HTML: Membuat Struktur Dasar HTML: Kode dimulai dengan deklarasi <!DOCTYPE html> yang menandakan bahwa ini adalah dokumen HTML5. Kemudian ada elemen <html> yang mengapit seluruh konten halaman web. Di dalamnya, ada elemen <head> yang berisi metadata dan elemen <body> yang berisi konten yang akan ditampilkan.
2.	Metadata: Di dalam elemen <head>, terdapat meta tag <meta charset="UTF-8"> yang menetapkan karakter set dokumen sebagai UTF-8 untuk mendukung karakter internasional. Ada juga meta tag <meta name="viewport" content="width=device-width, initial-scale=1.0"> yang mendefinisikan viewport untuk responsifitas halaman web di perangkat berbasis web.
3.	Title: Elemen <title> menentukan judul halaman web, yang akan ditampilkan di tab browser.
4.	External CSS: Terdapat link ke file CSS eksternal <link rel="stylesheet" href="./Style.css">. Ini menghubungkan file CSS dengan nama "Style.css" ke halaman HTML ini.
5.	Isi Halaman: Di dalam elemen <body>, terdapat berbagai elemen HTML yang akan ditampilkan di halaman web.
6.	Heading: Ada dua elemen heading <h1> dan <h2> yang menampilkan teks "CSS Selectors" dan "Applying CSS to different Parts of HTML" masing-masing.
7.	Paragraf: Elemen <p> menampilkan paragraf teks. Paragraf pertama memiliki kelas "note" dan akan diubah menjadi warna merah.
8.	Ordered List (Ol): Elemen <ol> menampilkan daftar yang diurutkan. Terdapat beberapa elemen <li> di dalamnya yang merupakan item-item daftar.
a.	Class Selectors: Item pertama dari daftar memiliki kelas "note" dan akan diubah menjadi font size 20px.
b.	ID Selectors: Item kedua dari daftar memiliki id "id-selector-demo" dan akan diubah menjadi warna hijau.
c.	Attribute Selectors: Item ketiga dari daftar akan diubah menjadi warna biru karena memiliki atribut value="4".
d.	Universal Selector: Item keempat dari daftar tidak memiliki modifikasi khusus, tetapi dalam instruksi, disebutkan bahwa semua elemen harus diubah menjadi teks yang rata tengah.
Hasil analisis :
•	Element Selector: Digunakan untuk menargetkan elemen berdasarkan nama tag HTML-nya. Contohnya adalah penggunaan untuk mengubah paragraf menjadi warna merah.Kode tersebut hanya memiliki satu elemen dalam body, yaitu sebuah judul <h1>. Teks dalam judul tersebut adalah "Style Me In Green".
•	Class Selector: Digunakan untuk menargetkan elemen-elemen dengan kelas tertentu. Kelas-kelas ini ditentukan dengan atribut class di dalam tag HTML. Dalam kode tersebut, class selector digunakan untuk mengubah gaya elemen-elemen yang memiliki kelas "note". Contohnya adalah mengubah ukuran font untuk semua elemen yang memiliki kelas "note" menjadi 20px.
•	ID Selector: Digunakan untuk menargetkan elemen-elemen dengan ID tertentu. ID ini ditentukan dengan atribut id di dalam tag HTML. Dalam kode tersebut, ID selector digunakan untuk mengubah gaya elemen dengan ID "id-selector-demo". Contohnya adalah mengubah warna teks menjadi hijau.
•	Attribute Selector: Digunakan untuk menargetkan elemen-elemen berdasarkan atribut-atribut tertentu atau nilainya. Dalam kode tersebut, attribute selector digunakan untuk mengubah gaya elemen dengan atribut value yang memiliki nilai 4. Contohnya adalah mengubah warna teks menjadi biru.
•	Universal Selector: Digunakan untuk menargetkan semua elemen di dalam dokumen. Dalam kode tersebut, tidak secara khusus diberikan contoh penerapan universal selector, namun dalam komentar terdapat instruksi untuk membuat semua teks menjadi rata tengah. Ini bisa dicapai dengan menggunakan universal selector dengan properti text-align: center;.

A.	Style.CSS
Baris HTML :
ol{
    margin-left: -40px;
    margin-top: -20px;
    list-style-position: inside;
}
p{
    color: red;
}
.note{
    font-size: 20px;;
}
#id-selector-demo{
    color: green;
}
li[value="4"]{
    color: blue;
}
*{
    text-align: center;
    font-family: 'Courier New', Courier, monospace;
}
Gambar Screen Shot Hasil Program 
 
4	Color Vocab Project
Baris HTML
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Color Vocab Project</title>
    <link rel="stylesheet" type="text/css" href="Color.css">
</head>
<body>
    <h1>Colors</h1>
    <h2>Learn the colors in Spanish</h2>  
    </br>
    <ol> 
        <li class="note" value="1" style="color: green;">Hijau</li>
        <img src="./Warna/Warna Hijau.jpg" alt="Warna Hijau" style="widht: 100px; height: 100px;"> <!-- Metode Inline -->       
        <li class="note blue" value="2" style="color: blue;"> Warna Biru </li> <!-- Metode Inline -->
        <img src="./Warna/Warna Biru.jpg" alt="Warna Biru" style="width: 100px; height: 100px;"> <!-- Metode Inline -->
        <li class="note yellow" value="3" style="color: yellow;"> Warna Kuning </li> <!-- Metode Inline -->
        <img src="./Warna/Warna Kuning.jpg" alt="Warna Kuning" style="width: 100px; height: 100px;"> <!-- Metode Inline -->
        <li class="note Cyan" value="4" style="color: cyan;">Warna Cyan</li>
        <img src="./Warna/Warna Cyan.jpg" alt="Warna cyan"> <!-- Metode Internal -->
         <style>
            img {
                width: 100px;
                height: 100px; 
            }
            .note Cyan{
                color: cyan;
            }
        </style>
        <li class="note Hitam" value="5" style="color: black;">Warna Hitam</li>   <!-- Metode Eksternal -->
        <link rel="stylesheet" href="styles.css">
        <img src="./Warna/Warna Hitam.jpg" alt="Warna Hitam">
    </ol>
</body>
</html> 

Style CSS Eksternal
img {
    width: 100px;
    height: 100px;
    color: black;
}

Gambar Screen Shot Hasil Program 
 

3. Kesimpulan
Kesimpulan dari semua hal di atas adalah sebagai berikut:
Kode HTML dan CSS yang digunakan untuk membuat halaman web sederhana yang menampilkan daftar warna beserta gambar-gambar yang sesuai. Berikut adalah kesimpulan tentang materi tersebut:
1.	HTML Structure (Struktur HTML) :
Kode HTML menyusun struktur dasar halaman web, termasuk judul, daftar, dan elemen-elemen konten lainnya.
2.	CSS Styling (Gaya CSS) :
a)	Kode CSS digunakan untuk mengatur tata letak dan gaya visual dari elemen-elemen HTML dalam halaman.
b)	Ini mencakup pengaturan margin, warna teks, ukuran font, dan gaya lainnya.
3.	Penggunaan Kelas dan ID :
a)	Kelas dan ID digunakan untuk memberikan gaya yang berbeda pada elemen tertentu dalam halaman.
b)	Kelas seperti note digunakan untuk memberikan gaya umum pada elemen-elemen yang sama, sementara ID seperti id-selector-demo memberikan gaya khusus pada elemen tertentu.
4.	Daftar Terurut (Ordered List) :
a)	Daftar terurut digunakan untuk menampilkan daftar item dengan nomor urutan.
b)	Dalam materi ini, daftar tersebut digunakan untuk menampilkan nama dan gambar warna dalam bahasa Spanyol.
5.	Pengaturan Warna dan Margin :
a)	Pengaturan warna teks, baik secara umum maupun berdasarkan kelas atau nilai atribut tertentu, menghasilkan tampilan yang beragam.
b)	Pengaturan margin mengontrol tata letak elemen-elemen dalam halaman, memungkinkan penyesuaian posisi relatif.
6.	Penggunaan CSS Selectors :
a)	Memperkenalkan berbagai jenis selector CSS seperti element selector, class selector, ID selector, dan attribute selector.
b)	Selector digunakan untuk menargetkan elemen HTML tertentu dan menerapkan gaya yang sesuai.
7.	Metode Penyisipan CSS :
a)	Laporan menguraikan tiga metode utama untuk menyisipkan CSS ke dalam halaman HTML: inline, internal, dan eksternal.
b)	Setiap metode memiliki kegunaan dan keunggulan masing-masing, tergantung pada kompleksitas proyek, konsistensi gaya, dan pemeliharaan kode.
8.	Inline CSS :
a)	Inline CSS diterapkan langsung ke dalam elemen HTML menggunakan atribut style.
b)	Metode ini cocok untuk perubahan gaya yang spesifik pada satu elemen dan tidak memerlukan file eksternal tambahan.
9.	Internal CSS :
a)	Internal CSS ditempatkan di dalam tag <style> di dalam bagian kepala (head) dokumen HTML.
b)	Ini memungkinkan gaya untuk diterapkan pada seluruh halaman atau sekelompok elemen tertentu di dalam halaman.
10.	Eksternal CSS :
a)	Eksternal CSS didefinisikan dalam file terpisah dengan ekstensi .css dan disisipkan ke dalam dokumen HTML menggunakan tag <link> di bagian kepala.
b)	Metode ini memisahkan struktur HTML dari gaya CSS, memungkinkan untuk manajemen gaya yang lebih efisien, konsisten, dan terstruktur.

