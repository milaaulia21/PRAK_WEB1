# LAPORAN PRAKTIKUM PEMROGRAMAN WEB 1
Tugas ini dilaksanakan dalam rangka memenuhi nilai Mata Kuliah Pemrograman Web yang diampu oleh Bapak Prih Diantono Abda'u, S.Kom., M.Kom
## HTML
HTML (Hypertext Markup Language) adalah bahasa markup yang digunakan untuk membuat halaman web. Biasanya digunakan untuk mendefinisikan struktur dan tata letak konten dari sebuah halaman web, termasuk teks, gambar, hyperlink, video, dan elemen-elemen lainnya. 
HTML bekerja dengan cara menandai elemen-elemen konten dalam dokumen dengan menggunakan tag-tag khusus. Setiap tag memiliki fungsi tertentu dalam menentukan bagaimana elemen tersebut akan ditampilkan oleh halaman web. 
### Line Break
Line break dalam HTML dalah cara untuk membuat teks atau konten HTML memulai baris baru menjadi beberapa baris terpisah. Line break biasanya digunakan dalam konteks seperti paragraf, teks dalam gambar, atau teks dalam elemen lain yang biasanya dianggap sebagai konten berjalan. 
Untuk membuat line break, kita menggunakan tag 'br'. Tag 'br' tidak memiliki tag penutup karena itu adalah tag tunggal. 

![alt text](https://github.com/milaaulia21/PRAK_WEB1/blob/main/images/line%20break%20(html).PNG?raw=true)

### Links
Elemen 'a' dalam HTML digunakan untuk membuat tautan atau hyperlink ke halaman web lain, dokumen, atau sumber daya online lainnya menggunakan atribut 'href'. Dengan atribut tersebut, pengguna dapat mengklik teks atau gambar dan diarahkan ke URL yang ditentukan.

![alt text](https://github.com/milaaulia21/PRAK_WEB1/blob/main/images/links%20(html).PNG?raw=true)

### Headings
Headings dalam HTML digunakan untuk memberikan struktur dan hierarki pada konten sebuah halaman web. Ada enam level heading yang tersedia, dimulai dari h1 hingga h6. Dimana h1 adalah yang paling besar dan paling penting, sedangkan h6 adalah yang terkecil. 

![alt text](https://github.com/milaaulia21/PRAK_WEB1/blob/main/images/headings%20(html).PNG?raw=true)

1. h1 : Heading level 1 digunakan untuk judul halaman. Biasanya hanya ada satu h1 dalam satu halaman web dan itu mewakili judul halaman secara keseluruhan. 
2. h2 : Heading level 2 digunakan untuk judul sub-seksi yang penting. Biasanya mengikuti h1 dan memberi struktur pada sub-bagian dari halaman web.
3. h3 : Heading level 3 digunakan untuk sub-judul di bawah h2. Memberikan struktur lebih lanjut pada konten dan dapat digunakan untuk menyoroti bagian-bagian penting dari sub-seksi. 
4. h4, h5, h6 : Heading level 4, 5, dan 6 digunakan untuk sub-judul lebih lanjut atau bagian-bagian yang lebih spesifik dari konten. Mereka memiliki ukuran dan tingkat kepentingan yang berkurang secara berurutan. 
### Horizontal Rules 
Horizontal rules dalam HTML digunakan untuk membuat garis horizontal yang memisahkan konten atau bagian-bagian tertentu dari halaman web. Garis Horizontal ini dapat digunakan untuk memberikan struktur visual pada halaman, memisahkan bagian-bagian konten, atau menandai transisi antara bagian-bagian yang berbeda. 
Elemen yang digunakan untuk membuat horizontal rules adalah 'hr'.

![alt text](https://github.com/milaaulia21/PRAK_WEB1/blob/main/images/horizontal%20rules%20(html).PNG?raw=true)

## CSS 
CCS (Cascading Style Sheets) adalah bahasa yang digunakan untuk mengatur tampilan dan format dari elemen-elemen HTML di dalam sebuah halaman web. Memungkinkan pengembang web untuk mengontrol warna, font, ukuran, tata letak, dan berbagai aspek tampilan lainnya dari elemen-elemen HTML.
### Selectors
Selector dalam CCS adalah cara untuk menentukan elemen HTML mana yang akan diberi gaya dengan aturan tertentu. Dalam menggunakan selector, kita dapat menargetkan elemen individu, sekelompok elemen, atau bahkan semua elemen dalam dokumen HTML. Biasanya untuk mengatur tata letak, warna, ukuran, dan berbagai properti gaya lainnya untuk mengubah tampilan dan perilaku elemen-elemen di halaman web. Dapat menciptakan desain yang konsisten dan menarik untuk situs web kita. 
1. Element Selector. Memilih elemen HTML berdasarkan nama elemennya. Menggunakan atribut 'p'.

    ![alt text](https://github.com/milaaulia21/PRAK_WEB1/blob/main/images/selector%20element%20(css).PNG?raw=true)

2. Class Selector. Memilih elemen HTML berdasarkan kelasnya. Menggunakan atribut '.class'.

   ![alt text](https://github.com/milaaulia21/PRAK_WEB1/blob/main/images/selector%20class%20(css).PNG?raw=true)
   
4. Id Selector. Memilih elemen HTML berdasarkan ID-nya. Menggunakan atribut '#id'.

   ![alt text](https://github.com/milaaulia21/PRAK_WEB1/blob/main/images/selector%20id%20(css).PNG?raw=true)
   
6. Universal Selector. Memilih semua elemen dalam dokumen. Menggunakan atribut '*'.
   
   ![alt text](https://github.com/milaaulia21/PRAK_WEB1/blob/main/images/selector%20universal%20(css).PNG?raw=true)

### Colors
Color dalam CSS, merujuk pada properti yang digunakan untuk menentukan warna teks di dalam sebuah elemen HTML. Properti ini biasanya untuk mengubah warna teks dari defaultnya (hitam) menjadi warna lain sesuai dengan preferensi desain kita. 

![alt text](https://github.com/milaaulia21/PRAK_WEB1/blob/main/images/colors%20(css).PNG?raw=true)

### Box Model 
Box model dalam CSS menggambarkan cara browser menangani elemen HTML dengan memperhitungkan empat komponen utama :
1. Content adalah bagian utama dari elemen yang berisi teks, gambar, dan lain-lain. Lebar dan tinggi content ditentukan oleh properti 'width' dan 'height'.
2. Padding adalah area transparan di sekeliling konten yang memberikan jarak antara konten dan batas elemen. Properti 'padding' digunakan untuk mengatur ukuran padding dalam elemen. Padding tidak memiliki warna atau gaya, hanya memengaruhi ruang di sekitar konten.
3. Border (Batas) adalah garis yang mengelilingi konten dan padding dari elemen. Properti 'border' digunakan untuk menentukan lebar, warna, dan gaya garis. Batas bisa berupa garis solid, putus-putus, bergelombang, dan gaya lainnya.
4. Margin adalah ruang di luar elemen yang memberikan jarak antara elemen tersebut dengan elemen-elemen lain disekitarnya. Properti 'margin' digunakan untuk mengatur ukuran margin. Margin tidak memiliki warna atau gaya, hanya memengaruhi ruang di luar elemen.

![alt text](https://github.com/milaaulia21/PRAK_WEB1/blob/main/images/box%20model%20(css).PNG?raw=true)

## JavaScript
JavaScript adalah bahasa pemrograman yang sering digunakan untuk mengembangkan aplikasi web interaktif. Biasanya memberikan kemampuan untuk mengontrol perilaku halaman web, membuat efek animasi, memvalidasi input pengguna, berinteraksi dengan server. JavaScript sangat penting dalam pengembangan web modern karena memungkinkan pengalaman yang dinamis dan interaktif.
### Variables
Variabel dalam JavaScript adalah simbol yang digunakan untuk menyimpan data. Ada beberapa cara untuk mendeklarasikan variabel :
1. 'var' : cara lama untuk mendeklarasikan variabel. Variabel yang dideklarasikan dengan 'var' memiliki lingkup fungsi, artinya hanya dapat diakses di dalam fungsi di mana itu dideklarasikan.

    ![alt text](https://github.com/milaaulia21/PRAK_WEB1/blob/main/images/var%20(javascript).PNG?raw=true)
   
2. 'let' : Memperkenalkan variabel yang dapat diinisialisasi ulang nilainya. Variabel yang dideklarasikan dengan 'let' memiliki lingkup blok yang hanya dapat diakses di dalam blok.

    ![alt text](https://github.com/milaaulia21/PRAK_WEB1/blob/main/images/let%20(javascript).PNG?raw=true)
   
3. 'const' : Mendeklarasikan variabel yang nilainya tidak dapat diubah setelah diinisialisasi. Variabel yang dideklarasikan dengan 'const' harus diinisialisasi saat deklarasi dan nilai mereka tetap tidak berubah setelahnya.

    ![alt text](https://github.com/milaaulia21/PRAK_WEB1/blob/main/images/const%20(javascript).PNG?raw=true)
   
