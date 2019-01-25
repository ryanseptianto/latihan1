# latihan1


## langkah-langkah cara penggunaan git hub
![gambar1](https://user-images.githubusercontent.com/46926758/51745083-5e5fc100-20d4-11e9-9031-489804ba1bcb.png)

  Apa itu git
Git adalah pengontrol versi yang bertugas mencatat setiap perubahan pada file proyek yang dikerjakan oleh banyak orang maupun sendiri. Git dikenal juga dengan distributed revision control (VCS terdistribusi), artinya penyimpanan database Git tidak hanya berada dalam satu tempat saja.

# Langkah-langkah Install GIT di berbagai jenis sistem

Install GIT di Windows

Menginstall GIT di Windows sangat mudah, cukup dengan mendownload dan menjalankan instalasinya. Ikuti langkah berikut ini untuk meng-install GIT di Windows:

   1.Buka website ini dan download installer GIT untuk Windows.
   2.Setelah download, buka file tersebut untuk menjalankan proses instalasi. Ikuti semua instruksi, klik Next dan Finish hingga semua proses instalasi selesai.
   
# PERINTAH DASAR GIT

   1. git init, perintah untuk membuat repository local
   2. git add, perintah untuk menambahkan file baru, atau perubahan pada file pada staging sebelum proses commit.
   3. git commit, perintah untuk menyimpan perubahan kedalam database git.
   4. git push -u origin master, perintah untuk mengirim perubahan pada repository local menuju server repository.
   5. git clone [url], perintah untuk membuat working directory yang diambil dari repositry sever.
   6. git remote add origin [url], perintah untuk menambahkan remote server/reopsitory server pada local repositry (working directory).
   
# Langkah-Langkah Menggunakan Git

   1. Klik kanan pada monitor Klik " Git Bash Here" 
      ![gambar2](https://user-images.githubusercontent.com/46926758/51747291-9fa79f00-20db-11e9-9d1f-abd0b4068ed5.png)

   2. Maka akan ada tampilan command prompt seperti dibawah ini
      ![gambar3](https://user-images.githubusercontent.com/46926758/51749328-a76a4200-20e1-11e9-9f62-6787c053a769.png)

   3. Buka Drive yang ingin dipakai, semisal Drive D jalankan dengan perintah cd /d
      ![gambar4](https://user-images.githubusercontent.com/46926758/51749368-bfda5c80-20e1-11e9-9b21-147b0f7b9cbf.png)

   4. Buat directory dengan printah "mkdir" sebagai contoh : directory Pemograman1 
      ![gambar5](https://user-images.githubusercontent.com/46926758/51749397-d1bbff80-20e1-11e9-8fee-9b75b3d9d1ec.png)

   5. Buka directory Pemograman1 dengan perintah cd Pemograman1
      ![gambar6](https://user-images.githubusercontent.com/46926758/51749441-ef896480-20e1-11e9-8f9f-77d893b5c553.png)

   6. Buat directory latihan1 dan buka directory latihan1.
      ![gambar7](https://user-images.githubusercontent.com/46926758/51749475-0e87f680-20e2-11e9-91ac-7454447d65d5.png)

   7. Menambahkan file baru pada repository dengan perintah echo "#latihan1" >> README.md 
      ![gambar8](https://user-images.githubusercontent.com/46926758/51749502-1fd10300-20e2-11e9-896b-7807678c1a37.png)

   8. Jalankan perintah git init untuk menjalankan repository local 
      ![gambar9](https://user-images.githubusercontent.com/46926758/51749532-30817900-20e2-11e9-9406-539afa4fc9d1.png)

   9. Untuk menambahkan file yang baru saja dibuat tersebut gunakan perintah git add README.md
      ![gambar10](https://user-images.githubusercontent.com/46926758/51749565-4858fd00-20e2-11e9-8b53-aa6bd9763994.png)

   10. Untuk menyimpan perubahaan yang ada kedalam database repository local, gunakan perintah git commit -m "File pertama saya"
      ![gambar11](https://user-images.githubusercontent.com/46926758/51749597-6161ae00-20e2-11e9-84d0-d6a7e00e09d1.png)

   11. Buat repository server, isi nama repositorynya semisal : latihan1 ,kemudian klik tombol Creat repository
       ![gambar12](https://user-images.githubusercontent.com/46926758/51749706-adacee00-20e2-11e9-83d8-e592f29bf53a.png)

   12. Menambahkan remote repository. remote repository merupakan repository server yang akan digunakan untuk menyimpan setiap perubahan        sehingga dapat diakses oleh banyak user.
       ![gambar13](https://user-images.githubusercontent.com/46926758/51749753-cfa67080-20e2-11e9-9bdb-e87f3bd39164.png)

   13. Mengirim perubahan ke server dengan perintah git push -u origin master
       ![gambar14](https://user-images.githubusercontent.com/46926758/51749810-f795d400-20e2-11e9-8a0e-d773aaafa39f.png)

   14. Melihat hasil pada repository, buka laman github.com arahkan pada repositorynya. Maka perubahan akan terlihat pada laman tersebut
       ![gambar15](https://user-images.githubusercontent.com/46926758/51749842-0e3c2b00-20e3-11e9-8e24-9ecda09f91ae.png)

   15. Buka drive D kemudian klik Pemograman1, klik latihan1
       ![gambar16](https://user-images.githubusercontent.com/46926758/51749861-201dce00-20e3-11e9-87a5-b227b4421d71.png)

   16. Klik kanan pada file Readme.md kemudian pilih aplikasi untuk mengubah file, semisal dibawah ini dengan aplikasi notepad 
       ![gambar17](https://user-images.githubusercontent.com/46926758/51749893-30ce4400-20e3-11e9-8693-f7785bf0a87f.png)

   17. Untuk mengirim perubahan jalan perinta git push -u origin master, kemudian git add README.md dan git commit -m "latihan1"
       ![gambar18](https://user-images.githubusercontent.com/46926758/51749930-4479aa80-20e3-11e9-80c3-642cf0f0ad89.png)

   18. Kemuidan lihat perubahannya pada laman github.com 
       ![gambar19](https://user-images.githubusercontent.com/46926758/51749959-56f3e400-20e3-11e9-8c5c-2c7fb4836cfb.png)

SEKIAN DAN TRIMAKASIH

NAMA  : RYAN SEPTIANTO
NIM   : 311810417
KELAS : TI 18 B1
