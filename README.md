
- Nama    : Doni Perdana Siringoringo
- NIM     : 312210687
- Kelas   : TI.22.B1



# Instalasi GIT dan Latihan menggunakan Version Control System

# - Instalasi GIT :

1.Download git di link berikut : https://git-scm.com/downloads

2.Berikut File Git yang sudah didownload lalu open :

![1](img/1.png)


3.Maka akan muncul infomasi lisensi Git, klik Next > untuk melanjutkan.

![2](img/2.png)

4.Selanjutnya menentukan lokasi instalasi. Biarkan saja apa adanya, kemudian klik Next >.

![3](img/3.png)

5.Selanjutnya pemilihan komoponen, biarkan saja seperti ini kemudian klik Next >

![4](img/4.png)

6.Selanjutnya pemlilihan direktori start menu, klik Next >.

![5](img/5.png)

7.Selanjutnya pengaturan PATH Environment. Pilih yang tengah agar perintah git dapat di kenali di Command Prompt (CMD). Setelah itu klik Next >.

![6](img/6.png)

8.Selanjutnya konversi line ending. Biarkan saja seperti ini, kemudian klik Next >.

![7](img/7.png)

9.Selanjutnya pemilihan emulator terminal. Pilih saja yang bawah, kemudian klik Next >.

![8](img/8.png)

10.Selanjutnya pemilihan opsi ekstra. Klik saja Next >.

![9](img/9.png)

11.Selanjutnya pemilihan opsi ekspreimental, langsung saja klik Install untuk memulai instalasi.

![10](img/10.png)

12.Tunggu beberapa saat, instalasi sedang dilakukan

![11](img/11.png)

13.Setelah selesai, kita bisa langsung klik Finish.

![12](img/12.png)


# Cara Pengguanan GIT :

1 .- ` git config --global user.name “name” `
    - ` git config --global user.email "email" `

![13](img/14.png)

![15](img/16.png)

2. Membuat repository / folder baru dan masuk repository tersebut dengan masukan perintah sebagai berikut :
- ` mkdir LatihanVCS `
  ` cd LatihanVCS`

![16](img/17.png)

![17](img/18.png)


3.Selanjutnya kita akan membuat file baru bernama README.md :
- ` echo "# LatihanVCS" >> README.md`

![18](img/19.png)

4.Lalu kita inisialisasi dengan perintah berikut :
- ` git init`

![19](img/20.png)


5.Setelah itu kita akan melihat status dari file tersebut :
- ` git status `

![20](img/21.png)

Terlihat disitu terdapat file README.md yang belum di tambahkan yang bertulis dengan warna merah

6.Untuk menambahkan file tersebut / perubahan pada file pada staging sebelum proses commit. ketikan perintah berikut

Lalu cek kembali status file tersebut jika sudah sukses di tambahkan tulisan file berwarna hijau

- `git add "README.md" `

- `git status`

![21](img/22.png)

7.Setelah itu simpan perubahan / penambahan yang terjadi dengan mengetikan perintah berikut :

- `git commit -m "first commit"`

- `git remote -v => untuk mengecek sudah terhubung dengan url server git`

![22](img/23.png)

Perubahan / penambahan pada repository berhasil disimpan didatabse lokal, Jika kita ingin menyimpannya diserver repository silahkan kunjungi link berikut : `https://github.com`

8.Lalu akan muncul tampilan sebagai berikut :

![23](img/24.png)


Silahkan login jika sudah memiliki akun namun jika belum silahkan daftar terlebih dahulu :

9.Lalu akan muncul tampilan sebagai berikut silahkan daftar 

![24](img/25.png)


Sampai semua ceklis berwarna hijau Jika sudah klik Continue


10.Membuat Repository baru digithub klik tombol create or new yang berwarna hijau 

![25](img/26.png)

- Public => repository dapat dilihat oleh semua orang
- Private => repository dibatas tidak semua orang bisa melihat

11.Jika Berhasil akan muncul tampilan sebagai berikut :

![26](img/28.png)

- 1 Untuk menyimpan repository jika di komputer lokal belum ada
- 2 Untuk membuat repository jika di komputer lokal sudah ada dan tersimpan kalian tinggal ikutin perintahnya

12.Baik sekarang kita akan push repository lokal kita ke github pertama kita lakukan remote sebagai berikut :

- `git remote add origin https://github.com/adam-webdev/LatihanVCS.git`
Lalu cek status remote apakah berhasil :

- `git remote -v`
Lalu kita bisa atur branch repository kita dengan menjalankah perintah berikut :
- `git branch -M main`


![29](img/Screenshot%20(123).png)


13.Selanjutnya kita push dengan menggunakan perintah :

- `git push -u origin main`

- `origin adalah nama remote yang tadi kita buat`

- `main adalah branch repository kita`


![30](img/30%20(2).png)



# Sekian cara penggunaan git yang bisa saya jelaskan terimaksih