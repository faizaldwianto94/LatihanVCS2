# LatihanVCS2

**NAMA :Faizal Dwianto** <br>
**KELAS :TI.20.A.1** <br>
**NIM :312010467** <br>
**TUGAS :MEMBUAT REPOSITORY** <br>

## Langkah-langkah penggunaan git

* Download Git terlebih dahulu, dengan link berikut ini : [click here](https://git-scm.com)

![contoh git-scm](ss4/GitScm.png)

* Setelah file terdownload, silahkan lakukan instalasi dengan referensi berikut ini : [Git Installation Guide](https://git-scm.com/book/en/v2/Getting-Started-Installing-Git)

![contoh foto installing](ss4/installing.png)

* Setelah installasi selesai, buka software GitBash pada menu di Windows, dan lakukan pengecekan versi, dengan mengetik syntax berikut : <br>

`git --version`

![contoh gambar mengecek version](ss4/version.png)


* Jika muncul tampilan git version, berarti Git sudah berhasil di install dan bisa digunakan. Langkah pertama kita harus mengkonfigurasi user nama dan email di Git, dengan mengetikkan syntax berikut : <br>

`git config --global user.name "masukan nama anda"` <br>
`git config --global user.email "masukan email anda"` <br>

![membuat user](ss4/user.png)


* Setelah diisi, silahkan lakukan pengecekan user nama dan email, dengan mengetikkan perintah berikut : <br>

`git config --global user.name` <br>
`git config --global user.email` <br>

![mengecek user](ss4/name.png)

* Buat akun di GitHub,seperti contoh dibawah ini.Dan lakukan Verifikasi akun melalui email yang sudah terdaftar.

* Jika akun GitHub sudah selesai dibuat dan di verifikasi,proses selanjutnya silahkan buat Repository seperti gambar dibawah ini: Penjelasan

> * `Repository Name : (Silahkan isi nama repository yang diinginkan, seperti contoh saya ingin membuat repository LatihanVCS)`
> * `Description : (Isi dengan deskripsi atau penjelasan tentang repository Anda)`
> * `Public / Private : (PIlih salah satu jenis repository akan bisa dilihan sama semua orang atau tidak)`
> * `Add a README.md file : Centang pada bagian ini jika Anda menginginkan file README.md ada di repository Anda`
> * `Add .gitignore : Merupakan sebuah file yang berisi daftar nama-nama file dan direktori yang akan diabaikan oleh Git.`
> * `Choose a license : Silahkan centang jika Anda memiliki lisensi pada repository yang akan dibuat Kemudian tekan tombol Create Repository untuk menyimpan`


![pembuatan nama repositori](ss4/buat.png)


* Jika repository sudah dibuat maka akan muncul tampilan seperti dibawah ini :


![hasil repositori](ss4/repositori.png)


* Pembuatan akun dan repository pada Github telah selesai, saat ini akan kita lakukan untuk me-remote repository Github pada GitBash Lokal. Bagaimana caranya? Langkah pertama kita harus menyalin link URL git kita di Github, dengan cara tekan tombol Code lalu klik Copy.


![copy link](ss4/code.png)


* Setelah Link URL git kita tercopy, Silahkan buka File Explorer pada Windows, kemudian pilih folder dimana kita akan mendownload Repository dari Github ke lokal. Kemudian Klik Kanan, Pilih Git Bash Here.


![click git bash here](ss4/GitBash.png)


* Pop Up Command Prompt (CMD) akan terbuka. Pada proses ini kita akan melakukan download file repository yang tadi dibuat, dengan mengetikkan syntax berikut : <br>

`git clone [URL] pada contohnya, saya akan memasukan git clone` <br>

https://github.com/faizaldwianto94/LatihanVCS2.git

![git clone](ss4/clone.png)

* Setelah proses cloning selesai, pada saat ini kita masih pada folder awal (master), kita harus masuk kedalam folder yang telah dicloning tadi yaitu LatihanVCS dengan mengetikkan syntax berikut :


`cd latihanVCS2`

![cd](ss4/cd.png)


* Saat ini kita sudah masuk kedalam folder LatihanVCS, Silahkan edit file README.md yang ada di File Explorer. Bisa menggunakan Text Editor (Sublime Text, Notepad, Notepad++, Visual Studio Code). Edit sesuai dengan keinginan. Aturan file .md (Markdown) bisa dilihat di Link berikut ini : [click here](https://guides.github.com/features/mastering-markdown/)


![contoh](ss4/ss.png)

* Setelah file README.md diedit, silahkan Simpan file tersebut dengan cara CTRL+S atau File -> Save

* Langkah selanjutnya setelah file disimpan, kita kembali pada App Git Bash (CMD). Ketik pada Git Bash seperti berikut ini : <br>


`git add .` <br>


![git add .](ss4/add.png)

* Setelah selesai melakukan git add . langkah berikutnya kita akan melakukan commit. Fungsi commit adalah untuk menyimpan perubahan yang dilakukan, tetapi tidak ada perubahan pada remote repository. Ketik pada App Git Bash seperti berikut ini : <br>

`git commit "Update README.md"` <br>


![commit](ss4/commit.png) <br>

* Git commit telah selesai di lakukan. Untuk saat ini akan melakuka Git Push, Git Push berfungsi untuk mengirimkan perubahan file setelah di commit ke remote repository. Silahkan ketik pada App Git Bash seperti berikut : <br>


`git push` <br>


![push](ss4/push.png) <br>

* Semua proses telah selesai, silahkan kembali ke Web Browser untuk melihat perubahan yang telah di commit dan push dari remote.



![hasil](ss4/sss.png)

#TERIMAKASIH
