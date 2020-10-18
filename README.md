# LatihanVCS
Membuat Tutorian GIT

**Nama : Moch. Aqilla Fasha**

**Nim : 312010367**

**Kelas : TI.20.A.2**

## Latihan 4 

 1. Langkah pertama membuat folder **Latihan4**, saya membuat foldernya di desktop.
 2. Klik kanan pada folder yang sudah dibuat tadi lalu klik terminal lalu akan muncul seperti gambar dibawah ini :
 
 ![image](https://user-images.githubusercontent.com/72904414/96359562-71cf7d00-113e-11eb-8c15-685ab9047c05.png)
 
 3. 	Kemudian buatlah folder dengan mengetik di terminal `mkdir latihan4`
 
 ![image](https://user-images.githubusercontent.com/72904414/96360315-510b2580-1146-11eb-8671-5eeba38c1d79.png)
 
 dan nantinya di folder program 1 didalam nya ada folder baru **latihan4**


4.	Langkah selanjut nya masuk kedalam folder **latihan4** dengan mengetik `cd latihan4`

masukan gambar

5.	Buatlah folder tersebut menjadi repo (repository) dengan cara `git init`.
	Jika benar akan seperti gambar di bawah ini:
    
masukan gambar
    
   jika sudah seperti ini artinya folder sudah menjadi repo. 


6.	Setelah itu buat file **README.md** dengan mengertik `(echo “latihan 1” >> 	README.md)`

masukan gambar

7.	Cara mengecek file tersebut ketik `git status` maka akan muncul sebagai berikut:

masukan gambar

warna merah tersebut berarti file belum di add.

8. 	Cara nya dengan mengetik `git add <file>` atau jika file yang merah lebih dari satu ( git 	add . )

masukan gambar

untuk mengecek nya ketik `git status`

masukan gambar

maka warna file nya akan berubah hijau, file sudah di add.

9.	Langkah selanjutnya commit file tersebut `(git commit -m “pesan”)`

masukan gambar

jika tidak ada masalah maka akan seperti gambar di atas.

10. Langkah selanjut nya buat lah akun di http://github.com  
11. Jika sudah memiliki akun buat lah repository baru **new repository** 

masukan gambar

12.	Langkah selanjutnya mengisi repository nya 

masukan gambar

- isi repository nya dengan nama “latihan1” ,untuk penamaan bisa di rubah sesui keperluan.	
- untuk description / pesan buat lah sejelas mungkin.
- pilih lah public 
- lalu create repository 

13.	Maka akan muncul seperti gambar berikut 

masukan gambar

copy link tersebut untuk menghubungkan dengan akun git yang ada di pc/ laptop.

14.	Cara menghubungkan nya dengan mengetik `git remote add origin <link>`

masukan gambar

15.	Langkah selanjutnya ketik `git push -u origin master`

masukan gambar

maka file sudah terhubung dengan akun github anda.

## Pesan
 - `mkdir <nama file>` untuk membuat file baru
 - `git init` untuk membuat depository local
 - `git status` untuk mrngcek apakah ada perubahan di dalam file 
 - `git add` untuk menambah kan file baru 
 - `git commit` untuk menyimpan perubahan kedalam database git.
 - `git remote` untuk menghubungka file ke github
 - `git push` untuk meng upload file ke github
