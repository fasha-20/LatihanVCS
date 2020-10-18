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

![image](https://user-images.githubusercontent.com/72904414/96360356-b4955300-1146-11eb-92d5-4612a3f57f65.png)

5.	Buatlah folder tersebut menjadi repo (repository) dengan cara `git init`.
	Jika benar akan seperti gambar di bawah ini:
    
![image](https://user-images.githubusercontent.com/72904414/96360386-12299f80-1147-11eb-9592-acc2cdcba39d.png)
    
   jika sudah seperti ini artinya folder sudah menjadi repo. 


6.	Setelah itu buat file **README.md** dengan mengertik ` (echo “latihan 4" >> 	README.md)`

![image](https://user-images.githubusercontent.com/72904414/96367868-8fbad300-117a-11eb-93b9-95fb3b9bad14.png)

7.	Cara mengecek file tersebut ketik `git status` maka akan muncul sebagai berikut:

![image](https://user-images.githubusercontent.com/72904414/96367912-cb559d00-117a-11eb-9612-247925dd6b15.png)


warna merah tersebut berarti file belum di add.

8. 	Cara nya dengan mengetik `git add <file>` atau jika file yang merah lebih dari satu ( git 	add . )

![image](https://user-images.githubusercontent.com/72904414/96367980-343d1500-117b-11eb-9ad6-0931a5c66c60.png)

untuk mengecek nya ketik `git status`

![image](https://user-images.githubusercontent.com/72904414/96368033-9f86e700-117b-11eb-907c-d9968c65cef5.png)

maka warna file nya akan berubah hijau, file sudah di add.

9.	Langkah selanjutnya commit file tersebut `(git commit -m “pesan”)`

![image](https://user-images.githubusercontent.com/72904414/96368145-6d29b980-117c-11eb-9243-4b6728ad7950.png)

jika tidak ada masalah maka akan seperti gambar di atas.

10. Langkah selanjut nya buat lah akun di http://github.com  
11. Jika sudah memiliki akun buat lah repository baru **new repository** 

![image](https://user-images.githubusercontent.com/72904414/96368208-e45f4d80-117c-11eb-803e-69ea42bc62a8.png)

12.	Langkah selanjutnya mengisi repository nya 

![fasha](https://user-images.githubusercontent.com/72904414/96368239-27b9bc00-117d-11eb-9da0-11275f9f3b3f.png)

- isi repository nya dengan nama “latihan1” ,untuk penamaan bisa di rubah sesui keperluan.	
- untuk description / pesan buat lah sejelas mungkin.
- pilih lah public 
- lalu create repository 

13.	Maka akan muncul seperti gambar berikut 

![image](https://user-images.githubusercontent.com/72904414/96368285-60599580-117d-11eb-949a-ce9a5fe7f283.png)

copy link tersebut untuk menghubungkan dengan akun git yang ada di pc/ laptop.

14.	Cara menghubungkan nya dengan mengetik `git remote add origin <link>`

![image](https://user-images.githubusercontent.com/72904414/96368323-8b43e980-117d-11eb-9615-eb67cba1220d.png)

15.	Langkah selanjutnya ketik `git push -u origin master`

<img width="471" alt="git pus -u origin" src="https://user-images.githubusercontent.com/72904414/96371343-753d2580-118b-11eb-8519-65fa920b036c.png">


maka file sudah terhubung dengan akun github anda.

## Pesan
 - `mkdir <nama file>` untuk membuat file baru
 - `git init` untuk membuat depository local
 - `git status` untuk mrngcek apakah ada perubahan di dalam file 
 - `git add` untuk menambah kan file baru 
 - `git commit` untuk menyimpan perubahan kedalam database git.
 - `git remote` untuk menghubungka file ke github
 - `git push` untuk meng upload file ke github
