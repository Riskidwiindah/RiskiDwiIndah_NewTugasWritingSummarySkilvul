## Pengenalan HTML Dasar


Pasti tak asing lagi dengan kata "HTML" Yup! bahasa yang digunakan para development web untuk membuat projek mereka. Hypertext Markup Language (HTML) sebagai pondasi dasar membuat website selain dari cSS dan Javascript. Perbedaan diantara ketiganya yaitu:

- HTML merupakan kerangka dasar dari sebuah website

- CSS berfungsi memperindah page HTML

- Javascript memberikan interaksi antara user dengan website

Sebenarnya banyak orang berfikir bahwa html ini termasuk bahasa pemograman. Namun setelah saya mengikuti kelas, bahwa html itu code pemograman yang didesain hanya untuk mendekomentasikan file-file secara online. Hal utama yang harus dipersiapkan:

1. Browser

2. Code Editor

Untuk code editor tools yang akan dibutuhkan untuk membuat HTML sangatlah beragam. Salah satunya saya menggunakan text editor VSCode. Alasan menggunakan VSCode yaitu karena aplikasi yang open source alias tidak berbayar, menyediakan banyak sekali extensions yang dapat dinstal secara gratis, dan juga apliaksi yang serba guna dapat dipake dengan berbagai format bahasa pemograman.

## Strukture HTML


HTML tersusun sebagai kesatuan dari sebuah tingkatan family ter relationship. terdapat dua istilah yaitu parent dan child. Jika terdapat element (p) didalam element (div) berarti itu dinamakan child, dan element (div) yang akan menjadi parent. Contoh struktur HTML:

![strukturHTML](/images/Screenshot%202022-09-25%20141441.png)

## Anatomi HTML


1. Opening tag yang ditandai dengan (<>)
2. Konten yaitu isi dari sebuag tagnya misal: Hello World!!
3. Closing tag yang ditandai dengan (</>)

## HTML Comment


Modal utama seorang programmer adalah dari codingannya. Alangkah baiknya codingannya pun dapat dimengerti oleh orang lain ataupun bagi rekan setimnya. Nah, disituasi itulah pentingnya comment hadir. Dimana comment ini tidak akan berpengaruh pada hasil codingan setelah di run. 

## Running program HTML


Dikarenakan kita sudah menggunakan VSCode justru sangat dimudahkan sekali dalam pengerjaan pengcodingan terutama running program. di extensions telah disediakan yang namanya "Live Server" yang dapat di instal secara gratis. Jika kita sebelumnya harus save file dulu setiap ada perubahan baru dicek di browser sekarang dengan adanya Live Server kita cukup melakukan save maka akan langsung terupdate pada browser. Live Server ini jdapat berjalan baik itu secara online maupun offline.

## HTML Tag Populer


1. Tag Image (img) berfungsi untuk menampilkan gambar di website. 
- atributenya: source (src) sebagai tempat link gambar yang ditampilkan baik itu online dari browser ataupun local directory
- atribute: alternative (alt) digunakan jika gambar tidak bisa kebuka pada halaman website, mungkin bisa karena faktor sinyal. Nantinya alt ini akan menampilkan teks nama gambarnya.
2. Tag Video (video) sama halnya tag img, tag video ini berguna menampilkan video pada halaman website
- atribute: controls berfungsi untuk menampilkan icon pause, play dan indikator menit.
3. Tag Table (table) berfungsi untuk membuat table pada halaman html
- Tag Table Row (tr) berfungsi untuk membuat baris pada table
- Tag Table Heading (th) berfungsi untuk menamakan kategori atau judul pada table
- Tag Table Data (td) bberguna untuk memasukkan data pada table.
4. Tag Form yaitu tag yang biasa digunakan untuk membuat halaman registrasi, data profile, dll di halaman html

## Semantic HTMl


Semantic artinya kita menggunakan element html yang sesuai dengan kebutuhan konten. diantaranya yaitu ada:
1. Tag artikel (articel)
2. Tag Side Bar (aside)
3. Tag Details (detail)
4. Tag figcaption
5. Tag Figure (figure)
6. Tag footer
7. Tag header
8. Tag main
9. Tag mark
10. Tag Navbar (nav)
11. Tag section
12. Tag summary
13. Tag time

Mengapa harus menggunakan semantic tag? terdapat berbagai keuntungan ternyata! diantaranya:
- Meningkatkan Accessibility
- Meningkatkan SEO
- Lebih mudah di maintain

## Deploy HTML


Hasil akhir membuat sebuah website yaitu dengan merilisnya di online agar semua orang dapat mengakses dengan mudah dimana pun dan kapan pun. Kegiatan tersebut dinamakan dengan prose deployment. Berbagai macam cara untuk mendeploynya, dapat membeli langganan web hosting dan domain. Namun kali ini yang saya pelajari yaitu dapat melakukan deployment web secara gratis menggunakan tools Netlify.
