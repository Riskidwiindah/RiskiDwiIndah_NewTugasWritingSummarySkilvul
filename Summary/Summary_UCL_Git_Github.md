## Pengenalan CLI dan Terminal


Sebelum ke pengenalan CLI terlebih dahulu penting memahami apa itu shell? jadi pengertian singkatnya shel itu sebuah program yang digunakan untuk berinteraksi dengan sebuah system. Untuk jenis dari shell itu sendiri salah satunya adalah Command Line Interface (CLI). Agar lebih paham dapat terlihat dari perbedaan antara GUI dan CLI:

- Graphical User Interface (GUI) yaitu shell yang sudah dipresentasikan menjadi visual interaktif, yang artinya dapat membedakan dengan mudah folder dan file. interaktifnya sendiri GUI cukup dengan di klik saja dapat mengakses dari satu folder ke folder lainnya.
- Sedangkan CLI shell yang masih berbasis text. jadi ketika ingin mengakses sebuah folder directori user akan memasukkan terlebih dahulu perintah yaitu semisal 'cd d:/'.

Sehingga jika dilihat dari segi efisiensi penggunaan GUI lah yang lebih baik ketimbang CLI. Tools yang digunakan untuk mengakses CLI itu disebut dengan Terminal Emulator.Contoh CLI sebagai berikut: Bourne Shell (sh), Bourne Again Shell (bash), Z shell (zsh) dan Command Prompt (cmd). Dari 4 contoh tersebut yang hanya dipelajari yaitu bash.

CLI ini memiliki pengaturan akan file systemnya sendiri. Cara sistem mengatur file Sebagian besar menggunakan konsep hirarki pohon.
![Gambar1](/images/Screenshot%202022-09-24%20223551.png)

Selanjutnya terdapat macam-macam navigasi perintah yang dibutuhkan untuk mengakses directory:
1. Print Working Directory (pwd) digunakan untuk menampilkan posisi user mengakses directorynya.
2. Lists (ls) digunakan untuk menmpilkan isis directory
3. Change Directory (cd) digunakan user untuk berpindah-pindah directory.

Macam-macam perintah untuk membuat files dan directory:
1. Touch (touch) digunakan untuk membuat file
2. Make Directory (mkdir) digunakan untuk membuat directory baru

Macam-macam perintah untuk melihat isi file:
1. Cat (cat) digunakan untuk melihat isi file secara keseluruhannya
2. Tail (tail) digunakan untuk melihat isi file baris terakhirnya saja
3. Head (head) digunakan untuk melihat isi file baris awalnya saja

Macam-macam perintah untuk menyalin, memindahkan dan menghapus file dan directory:
1. Copy (cp) digunakan untuk menyalin file dan directory. FYI: tambahkan '-R' untuk menyalin directory
2. Move (mv) digunakan untuk memindahkan file dan directory. FYI: tambahkan '-R' untuk memindahkan directory
3. Remove (rm) digunakan untuk menghapus file dan directory. FYI: tambahkan '-R' untuk menghapus directory

## Pengenalan Git dan Github


Git merupakan alat yang digunakan sebagian besar programmer sebagai version control system yang artinya mencatat sestiap ada perubahan pada file. Tools ini sangat membantu sekali ketika programmer bekerja dalam team.
cc
1. Contoh untuk melakukan setup awal pada aplikasi Git:
![setup_awalGit](/images/Screenshot%202022-09-25%20092208.png)

untuk username dan email saya samakan dengan akun Github yang saya punya. Jika ingin mengubahnya cukup kalian timpa lagi perintah git config tersebut dengan username dan email yang baru. Setelah melakukan setup, untuk mengecek keberhasil dalam mensetupnya kita menggunakan perintah berikut:
![cek_setUpBerhasil](/images//Screenshot%202022-09-25%20092857.png)

Maka akan mengeluarkan berupa list, jika berhasil pada bagian bawah terdapat username dan email yang telah diset up sebelumnya.

2. Setiap repository Git hanya untuk satu proyek saja. untuk lebih jelasnya 1 repository = 1 directory = 1 proyek/projek. Untuk membuat repository dapat dilakukan di akun Github sebagai global repository. Selanjutnya membuat folder di local directory yang akan digunakan sebagai local repository. kemudian gunakan perintah sebagai berikut:
![membuatGitInit](/images//Screenshot%202022-09-25%20095813.png)

Jika telah selesai melakukan initialization maka akan dengan mudah menggunakan git status, git add, git commit, dll pada folder guna mencatat setiap perubahan yang ada pada file.

3. Menghubungkan repository global yang ada di Github dengan repository local menggunakan perintah git remote:
![menghubungkanGitdenganGithub](/images/Screenshot%202022-09-25%20111655.png)

4. Memasukan file repository local ke Github yaitu dengan menggunakan perintah git push:
![memasukanKeGithub](/images/Screenshot%202022-09-25%20111730.png)

Setelah memasukkannya maka akan terjadi perubahan pada repository yang sudah dibuat di akun Github
1[hasilnya](/images/Screenshot%202022-09-25%20111816.png)


