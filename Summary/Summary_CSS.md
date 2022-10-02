## Pengenalan CSS


Banyak dari kita pasti mempertanyakan bagaimana sebuah website bisa membuat tampilan yang menarik, coloful, aesthetic, dan mempunyai ciri khasnya. Jika telah memiliki pertanyaan seperti itu, maka tepat sekali dengan pengertian dari Cascading Style Sheet (CSS). CSS ini merupakan bahasa yang diperlukan sekali oleh HTML untuk mendesain, memperindah sebuah halaman website. HTML dan CSS bagaikan teman sejoli yang tidak akan pernah terpisahkan eaaaaa:). Dengan CSS web development dapat dengan mudah menyalurkan kreasinya, seperti mengubah warna, editing font yang digunakan, layoting, dll.

## Element CSS & Comment


Syntax dari CSS yaitu:
1. Terdapat element HTML yang mau di styling
2. Terdapat properti CSSnya
3. Sebuah properti sangat tidak lengkap bila tidak ada valuenya

Kemydian alangkah baiknya sebuah codingan disertakan dengan comment, agar oranglain dapat mengerti codingan yang dikerjakan. Comment ini akan sangat penting bila mengahdapi situasi dimana memerlukan kerjasama dengan programmer web yang lain. Dan tentu comment ini tidak akan menyebabkan error ketika programmer merunningnya, sebab tidak akan dieksekusi oleh komputer. Comment ini digunakan hanya antara sesama programmer.

## Penggunaan CSS


Dalam penggunaannya CSS memiliki 3 cara:
1. Inline CSS yaitu menyisipkan atribute CSS (style) pada tag html. Contohnya: 
Tag p style="bacground-color: red; color: white;"

Dari contoh tersebut dapat dianalisis penggunaan CSSnya berupa background color dan warna dari fontnya. FYI jika kita menggunakan inline css pada tag yang sama menggunakan penulisan internal atau eksternal css, maka yang akan diekseskusi terlebih dahulu yaitu inline css.
2. Internal CSS yaitu menambahkan tag style di dalam file index HTML. 
![contohInternalCSS](/images/Screenshot%202022-09-26%20182945.png)

pada gambar terlihat bahwa h1 diberi styling yaitu atribute color dengan value warna biru.
3. External CSS yaitu membuat file baru dengan nama "styles.css" pada direktori yang sama dengan index.html. Setelah membuatnya maka hubungkan file css dengan file htmlnya menggunakan tag link dengan atribute hrefnya adalah nama file cssnya.

## Macam-Macam Cara Styling dengan CSS


- Tag name yaitu memanfaatkan element html untuk melakukan styling. Contohnya: jika kita ingin mestyling element h1, maka kita cukup panggil elementnya saja kemudian isi style stribut dan valuenya. Namun kelemahannya menggunakan cara ini yaitu setiap ada element h1 maka akan memiliki style yang sama.
- Class name yaitu cukup melakukan pemanggilan nama class sebagai atribut htmlnya. untuk membuat class css kita hanya membutuhkan '.' sebagai modal awal. jadi semisal kita ingin membuat style css dengan menggunakan class maka cukup menuliskan ".container". Setelah itu baru melakukan pemanggilan di file htmlnya.
- ID name Berbeda dengan Class Name. ID Name bersifat unik artinya hanya ada 1 nama ID pada 1 element HTML.Umumnya digunakan pada file HTML yang memiliki satu element khusus. Misal: tag nav ingin kita style dengan iD name, maka setelah dibuat stylenya cukup menggunakan atribut id pada tag nav lalu panggil nama iD name CSSnya. Oh iya untuk syntax penulisan ID name menggunakan symbol '#'.
- Nested element memanfaatkan tag html yang memiliki hubungan parent and child yaitu di dalam tag terdapat tag lagi.
- Flexbox digunakan untuk mengatur layouting sebuah web. flexbox yang biasa digunakan adalah flex direction, flex wrap, flex flow, justify content, align items, align content.