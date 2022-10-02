## Alghoritma 


Taukah kalian tanpa kita sadari bahwa selama ini setiap tindakan kita itu mencerminkan proses alghoritma. Pasti kalian langsung bingungkan apa itu alghoritma? Jadi pengertian alghoritma yaitu tahapan-tahapan yang tersusun secara sistematis sehingga membentuk suatu proses. Syarat dari suatu alghoritma ialah: kejelasan setiap step by stepnya, terdapat input dan menghasilkan output, serta mengandung suatu code dari bahasa pemograman yang ditentukan.

Kemudian kenapa kita harus mempelajarinya? Sebab di saat kita membuat program alghoriitma ini adalah modal penting guna memahami cara kerja atau akur dari codingan yang dibuat. Alghoritma sendiri memiliki 3 jenis diantaranya:

1. Algoritma Deskriptif. Cukup mudah pengaplikasian alghoritma jenis ini, dengan bahasa sehari-hari dan setiap tahapan ditulis secara berututan sudah dapat dikategorikan alghoritma jenis ini.
2. Alghoritma Flowchart. alghoritma ini sudah mulai menggunakan bahasa codingan yang digunakan serta dibantu dengan bentuk-bentuk persegi, jajargenjang, dll disetiap tahapannya. 
3. Algoritma Pseudocode. Algoritma jenis ini lebih mendekati bahasa code yang akan dibuat. Biasanya akan ditulis dengan format bahasa inggris. 

## Pengenalan Java Script


Java Script(JS) bukanlah Java karna mereka berbeda. JS berguna sekali membuat sebuah website dapat melakukan intaraksi dengan penggunanya dan merubah website yang awalnya statis menjadi dinamis. Menjalankan JS cukup dengan mempersiapkan browser seperti google, mozilla dll. Contoh syntax JavaScript:
1. Alert() yaitu mempilkan alert seperti pop up kotak dialog
2. Prompt() digunakan apabila membutuhkan inputan data dari pengguna. Nantinya akan mucul seperti kotak dialod yang terdapat kolom inputan.
3. Confirm() dibutuhkan untuk mengkonfirmasi sesuatu pada user. akan muncul kotak dialog dan pengguna diberiberi button suatu pilihan.
4. Console.log yaitu hal dasar yang wajib diketahui berfungsi untuk menguji logika program yang dibuat atau print data yang akan ditampilkan di bagaian console pada browser
5. comment. Kegunaan comment masih sama yaitu untuk menjelaskan code program kepada sesama programmer. Terdapat 2 macam comment: single comment (//) dan multiline comment (/**/)

## Tipe Data & variabel JS


Javascript memiliki 6 tipe data:
1. Number
2. String
3. Boolean
4. Null
5. Undefined
6. Objek

Pada javascript punterdapat penggunaan variabel. Variabel itu digunakan sebagai tempat penampunya nilai. Ada 3 macam variabel:
1. Var
2. Let
3. Const

Perbedaan diantaranya ialah jika menggunakan var setiap ada nama variabel yang sama ia akan selalu berubah sesuai varibel yang terbaru. Jika menggunakan let apabila terdapat inisialisasi nama variabel yang sama maka langsung error. Jika menggunakan const nilai atau value variabelnya tidak bisa diubah. 

## Operator JS


1. Assigment operator. Operator yang digunakan untuk memasukan nila kedalam variabel (=)
2. Aritmatik operator. operator yang melibatkan operasi matematika. Contohnya: +, -, *, /, %
3. Comparison operator. digunakan untuk mengcompare, membandingkan dua nilai yang menghasilkan teru or false. Contohnya: <, >, <=, >=, ==, ===, !==, !=
4. Logical operator. umumnya digunakan untuk melogika suatu kondisi kemudian menghasilkan nilai tru or false. Contoh simbolnya: && (dan), || (atau), ! (tidak)

## Conditional JS


Artinya kita sudah memasuki pembahasan pembuatan sebuah kondisi di javascript. jika ada kondisi maka tak luput dengan penggunaa if, else if, dan else. Untuk lebih jelasnya: if (jika), else if (jikalau), dan else (kondisi akhir dari kondisi sebelumnya). sysntax penulisannya yaitu:

if (kondisi){
    aksi
} else{
    aksi
}

atau

if (kondisi){
    aksi
} else if(kondisi){
    aksi
}else{
    aksi
}

Tidak hanya menggunakan if kita juga dapat menggunakan syntax switch. Contohnya:

switch (kondisi){
   case x:
    aksi
    break
    case y:
    aksi
    break
    default:
    aksi
}

Penggunaa switch disetiap casenya diwajibkan ada break sebagai penanda jika kondisi true maka pemeriksaan akan berhenti.

## Looping JS


Pengulangan (looping) digunakan jika sebuah kasus yang memerlukan pengulangan. Intinya apabila terdapat kasus yang memerlukan menampilkan banyak nilai, kita tidak mungkin menuliskannya satu persatu. Maka diperlukannya looping. looping sendiri terdapat berbagai macam yaitu for, while, do while. 
1. For loop. Kondisi perulangan yang sebelumnya kita sudah mengetahui berapa jumlah pengulangan yang dibutuhkan. Jadi systx penulisannya:
 for (kondisi awal; kondisi akhir; incerement){
    aksi
 }

 hasilnya:

 for (let i=0; i<8; i++){
    console.log(i)
 }

 2. While. penggunaan perulangan ini ketika terjadi kasus yang kita tidak tahu akan berapa kali pengulangan ini dilakukan. Contoh:
 while (kondisi) {
    aksi
 }

hasilnya:

let i=0
while (i<100){
    console.log(i)
    i++
}

pembahasannya selama i kurang 100 maka akan melakukan print terhadap nilai i, lalu i melakukan incerement dan terus akan berulang.

3. do while. pengulangan ini setidaknya akan menghasilkan satu kali hasil. Contoh syntaxnya
do {
    aksi
} while (kondisi)

## Scope JS


Apa itu scope JS? Menurut saya scope merupakan batasan akses sebuah variabel di javascript. Setiap bahasa pemograman pasti memiliki aturan scopenya masing-masing, dan pada umumnya semua bahasa pemograman memiliki pettern yang sama tentang 2 jenis scope yaitu:
1. Global scope. Seperti namanya yaitu Global yang artinya dapat diakses, dipanggil atau digunakan bebas tanpa ada halangan syarat sebab sifatnya yang umum. Namun syarat apabila variabel tersebut dapat dikatakan global scope yaitu inisialisasinya harus berada diluar block.
2. Local scope. kebalikan dari global scope, local scope lebih membatasi sebuah variabel untuk digunakan, yang artinya variabel itu tidak akan berjalan selama masih didalam block. Dan didalam pemanggilanya kita haru menyertakan nama induk terlebih dahulu atau memanggil nama induknya saja.

let angka = 100
function bilangan(){
    angka =+ 50
    return angka => menghasilkan angka 150
}
console.log (angka) => menghasilkan angka 100
console.log (bilangan())

Jadi untuk global scope yaitu variabel angka pada console.log akan mengikuti variabel angka yang berada diluar block yang hasilnya 100. Sedangkan untuk local scope, console.log kedua ia hanya akan mengikuti function/induknya. jika ingin mengakses isi dari function maka penulisannya:

console.log (bilangan.angka)

## Function JS


sebelum kita menganalogikan function dari segi pemograman, kita akan menganalogikan terlebih dahulu dari segi sehari-hari. Arti bahasa indonesia dari kata function ialah "fungsi". Baik mahluk hidup atau benda mati memiliki fungsinya masing-masing, dan fungsi itu merepresentasikan kegunaan dan kebermanfaatannya suatu benda atau suatu mahluk. Begitu pun dalam pemograman bahwa function dibutuhkan untuk menjalankan atau mengoperasikan aplikasi agar sesuai dengan kegunaanya. Dan sebuah function hanya akan menjalankan satu proses kerja. Ciri khas function yaitu adanya "()"

Contohnya: pada mesin cuci. ia memiliki 2 buah fungsi yaitu mencuci dan mengeringkan. Yang artinya mencuci dan mengeringkan merupakan dua proses yang berbeda.

- Penulisan sebuah function

function namaFunction(){
    aksinya
}

- Memanggil function

Dapat melakukan pemanggilannya dengan langsung menyebutkan nama fungsinya. Contohnya: mencuci()

- Parameter function
Dengan parameter, function dapat menerima sebauh inputan data dan menggunakannya untuk melakukan tugasnya. Ibaratkan jika kita ingin mencuci baju maka kita sbelum mencuci harus mempersiapkan perlatannya terlebih dahulu seperti sikat, sabun, air dan ember. Maka dari itu didalam pemograman peralatan mencuci dikatakan sebagai parameter/data yang dibutuhkan guna menjalankan function. Contohnya:

- Argument function 
Berbeda dengan parameter, argument merupakan sebuah value yang diberikan disaat kita memanggil atau mengakses function. 

Contohnya:

function mencuci (sabun, air, sikat, baju){ =>penerapan parameter
    aksi
}
console.log (mencuci(1, 20, 1, 10)) => penerapan argument

Kalau diarikan sabun memiliki value 1, air veluenya 20, sikat veluenya 1 dan baju veluenya 10.

- Default parameter
Menurut saya dengan adanya default parameter sebagai error handling di function. Sebab jika suatu function tidak diberikan argument saat dipanggil maka function tersebut akan tetap berjalan dengan diberi nilai awalan yang telah di setting.

- Function helper
Yaitu menggunakan function didalam function.

- Arrow function
Merupakan bentuk upgrade dari function klasik. Bentukanlama sebuah function sebelum arrow fuction yaitu seperti contoh option pertama. Sedangkan arrow function cara penulisannya yaitu:

function mencuci = () => {
    aksi
}

Jadi perbedaanya hanya terletak di (=) dan tanda arrownya (=>).

## Type Data JS (properties & method)


Tipe data dalam javascript terbagi menjadi dua kategori:
1. Type Data primitif yaitu tipe data yang mmasih standar/default yaitu String, Boolean, Undifined, Number dan Null.
2. Type Data non primitif/objek yaitu tipe data hasil pengembangan

Properti dan Method yang dimiliki oleh tipe data primitif:

1. String
- Property: 
String length berguna untuk mengecek panjang karakter dari sebuah string. 

- Method
String toUpperCase() berfungsi mengubah string menjadi huruf kapital.

string toLowerCAse() berfungsi mengubah karakter didalam tipe data string menjadi huruf kecil

String chartAt() berguna mengembalikan satu karakter dari posisi indeks yang telah diberikan. 

String includes() berfungsi untuk melakukan pencarian, yaitu jika benar maka akan mengembalikan nilai true dan jika salah maka akan mengembalikan nilai false.

String split() membutuhkan sebuah pola dari pola tersebut ia akan membaggi string tersebut dan dari hasil splitnya akan disimpan dalam bentuk array. 

2. Number
- Property
Number NaN digunakan untuk mengecek number. Dan dari hasil ia akan mereturn nilai false and true.

Math.pi digunakan jika ingin mendapat sebuah nilai pi 

Math.Log2E digunakan untuk mencari logaritma

Math sqrt berfungsi untuk mencari hasil akar bilangan

- Method
Number toString() berguna mengubah number menjadi string.

Number toFixed() berfungsi menentukan banyaknya angka dibelakang koma.

Math pow() berguna menghasilkan nilai pangkat

Math round berguna membulatkan angka koma menjadi angka desimal ke atas.

Math random() digunakan mengembalikan nilai angka secara acak. 

## Prototype JS


merupakan mekanisme javascript objek mampu menurunkan satu fiturnya ke fitur yang lain. di prototype juga dapat mengcustom method sendiri.

## Pengenalan DOM

Stelah mempelajari tentang tipe data, array. objek, function, operator javascript. kali ini kita akan belajar hal terpenti di javascript yaitu DOM. Pasti awalnya bingun bagaimana sih javascript mengolah data dari html dan menghubungkannya ke server atau database. Nah, itu merupakan kegunaan utama dari DOM. Document Object Model (DOM) merupakan jembatan antara bahasa pemograman dan dokumen html agar kedua dapat berinteraksi. DOM pada javascript dapat mengubah, memanipulasi tampilan atau struktur html. DOM menganut konsep tree struktur. Penggunaan DOM lebih banyak diimplementasikan pada Java script, namun DOM bukanlah bagian dari javascript melainkan sebuah web API

#### Traversing DOM


1. Ke bawah: 

- getElementById yaitu ia akan mengembalikan sebuah element dengan sspesifikasi valuenya. Apabila DOM tidak menemukan idnya maka ia akan mengembalikan nilai null.
- getElementsByClassName yaitu ia akan mengembalikan data dalam bentuk html collection (kumpulan dari beberapa elemnt) berdasarkan nama classnya
- getElementsByTagName yaitu digunakan mencari berdasarkan nama tag. dan mengembalikan dalam bentuk html collection.
- querySelectorFamily 

query Selector digunakan untuk menselect class, id, dan tag html. dan akan mengembalikan sebuah element yang dicari.

querySelectorAll sama fungsinya dengan query selector namun outputnya akan mengembalikan sebuah node list.

- clidren digunakan ketika ingin mengakses data child lewat parentnya. Contohnya: console.log (list[0].children). List merupakan sebuah nama class yang menjadi parentnya

2. Keatas: 

- parentElement digunakan untuk mengetahui parent element namun mengaksesnya lewat childnya. Kemudian mengembalikan ouput berupa element parentnya. 
- closest

3. Kesamping: 
 
- nextElementSibling digunakan umtuk mencari element sesudahnya
- previouseElementSibling digunakan untuk mencari sodaranya/kakak pada element atau juga bisa mencari element sebelumnya

#### DOM Manipulation


- innerHTML menambahkan konten pada element html lewat javascript
- innerText menambah konten berupa string

Perbedaan innerHTML dengan innerText => innerHTML implementasi elemen html kalo text cuma nampilin string aja. DOM juga menganut konsep single page aplikasi yaitu hanya mempunyai satu halaman. dan juga nnti halamannya gak ada reload diatas link pagenya

- append berguna menyisipkan element pada html lewat JS
- appendChild untuk menambahkan element child di element parent tapi diletakkannya di akhir
- remove digunakan untuk menghapus element
- atributes diguganakan apabila ingin mengetahui sebuah element mempunyai atribute apa aja.
- getAttribute digunakan untuk melihat isi dari attributenya
- setAttribut(attribute, value) digunakan jika ingin menambahakan attribute di sebuah element

#### Events dan Form

1. Events suatu interaksi yang diberikan user  ke sebuah website. contohnya berupa kegiatan scroll, klik. Untuk memberikan events terdapat 3 cara:
- Pada atribute html. Contohnya:

h1 onclick="alert('Selamat Datang')">Hallo<

- Memberikan sebuah event property. Contohnya:

let paragraf = document.getElementById("paragraf")
function tampilkanAlert(){
    alert("ini alert")
}

- Menggunakan addEventListener

let button = document.getElementById("btn")
button.addEventListener("click",function(){
    alert("ini dari button")
})