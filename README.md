<div align="center"> 
   <img src="https://git-scm.com/images/logos/downloads/Git-Icon-1788C.svg">
   <h1 align="center">Bekerja Dengan Git Bash</h1>
   <a <img alt="" src="https://img.shields.io/badge/version-2.39.1-brightgreen"></p></a>
   <a aria-label="Join the community on GitHub" href="https://git-scm.com/">
    <img height="25px" alt="" src="https://img.shields.io/badge/version-2.39.1-brightgreen?style=for-the badge&logo=git&labelColor=000000&logoWidth=20=">
  </a>
  <a aria-label="Join the community on GitHub" href="https://git-scm.com/community">
    <img height="25px" alt="" src="https://img.shields.io/badge/Join%20the%20community-blueviolet.svg?style=for-the-badge&logo=git&labelColor=000000&logoWidth=20">
  </a> 
</div>
 


<br/><br/>
 
 ### Berikut Adalah Command Git Yang Bisa Dipakai Di Git Bash
 
<br/>

# - GIT SETUP<br>

### • git config --global user.name “[name]”
Perintah ini menetapkan nama pengguna, yang membantu dalam meninjau oleh siapa perubahan itu dibuat.Usahakan username kalian sama dengan username github kalian agar bisa menjalankan perintah `git remote` untuk meremote repository di github
#### Example : 
```
git config --global user.name "yourname"
```

<img src="https://i.ibb.co/8s210Zz/faa9836e-b599-4c23-90db-3891260beff4.jpg" alt="faa9836e-b599-4c23-90db-3891260beff4" border="0">


### • git config --global user.email “[email address]”
Perintah ini menetapkan alamat email, inturn ini membantu dalam pelacakan oleh siapa aktivitas commit atau penggabungan dibuat.
#### Example :
```
git config --global user.email "yourgmail@gmail.com"
```

<img src="https://i.ibb.co/FBbg6qf/79af1e5e-6d98-4018-9e80-9ba83d4b42f8.jpg" alt="79af1e5e-6d98-4018-9e80-9ba83d4b42f8" border="0">


### • git config --global color.ui auto
Perintah ini menetapkan efek pewarnaan baris perintah otomatis agar mudah ditinjau.
#### Example :
```
git config --global color.ui auto
```

<img src="https://i.ibb.co/1vX0gdv/0246eed6-7e2f-4f51-a4c9-16e5c652d5ca.jpg" alt="0246eed6-7e2f-4f51-a4c9-16e5c652d5ca" border="0">

<hr>

# - CREATE AND INITIALIZE<br><br>

### • git init
gunakan `git init` ketika kalian sudah berada di repository tersebut (jalankan git bash ketika kalian sedang ada di folder yang ingin di jalankan agar memudahkan untuk initialize),Jika kalian sudah menjalankan `git init` maka akan ada status `(master)` di sebelah repository kalian
#### Example : 
```
git init
```

<img src="https://i.ibb.co/PYHBbNm/de46675c-899e-423f-bdb8-20140c9dcf64.jpg" alt="de46675c-899e-423f-bdb8-20140c9dcf64" border="0">


### • git clone [url]
Perintah ini digunakan untuk mendapatkan seluruh repositori atau mengunduh kode sumber yang ada dari URL yang disediakan. Pada dasarnya membuat salinan identik dari versi terbaru dari repositori di sistem lokal.
#### Example :
```
git clone https://github.com/SCFJR/Web-Sederhana.git
```

<img src="https://i.ibb.co/Gv3vF78/5153ef62-cde2-4238-ab3d-850ed476212d.jpg" alt="5153ef62-cde2-4238-ab3d-850ed476212d" border="0">

<hr>

# - STAGING & COMMIT<br>
![#f03c15](https://via.placeholder.com/15/f03c15/f03c15.png) Red color (in git status) = Untracked / Modified (tidak bisa di commit)<br>
![00b037](https://via.placeholder.com/15/00b037/00b037.png) green color (In git status)= In Staging Area (bisa di commit)<br><br>

### • git status
digunakan ketika kalian ingin melihat status file pada repository kalian yang ingin di commit 
#### Example :
```
git status
```

<img src="https://i.ibb.co/q0htKnv/eb648dbe-17aa-4875-b8dd-a864bcbe551a.jpg" alt="eb648dbe-17aa-4875-b8dd-a864bcbe551a" border="0">


### • git add [nama file]
Perintah ini memindahkan file dari working tree ke Staging area / branch saat ini.<br>
<sub>gunakan `git status` untuk melihat file yang masih berstatus Utracked atau modified kemudian add file yang masih berstatus Untracked / Modified dengan `git add` agar pindah ke dalam staging area</sub><br>

#### Example :
```
git add testedfile.html
```

<img src="https://i.ibb.co/2Nz8WKY/9dfc0f8a-8b9e-4cbe-8233-1db39e06095e.jpg" alt="9dfc0f8a-8b9e-4cbe-8233-1db39e06095e" border="0">


### • git add *
Perintah ini menambahkan satu atau lebih file dari working tree ke Staging area / branch saat ini. penggunaan `git add *` tidak memindahkan semua file kedalam staging area,melainkan hanya beberapa file yang dipindahkan ke staging area (antara 2 file tau lebih)<br>
<sub>gunakan `git status` untuk melihat file yang masih berstatus Utracked atau modified kemudian add file yang masih berstatus Untracked / Modified dengan `git add *` untuk memindahkan beberapa file ke dalam staging area</sub>
#### Example :
```
git add *
```

<img src="https://i.ibb.co/7jdjz6f/7fe11b29-03e1-4f9c-aeb2-da5fdb440aa2.jpg" alt="7fe11b29-03e1-4f9c-aeb2-da5fdb440aa2" border="0">


### • git add .
Tahapan memindahkan semua file di seluruh repositori ke Staging area / branch saat ini.<br>
<sub>gunakan `git status` untuk melihat file yang masih berstatus Utracked atau modified kemudian add file yang masih berstatus Untracked / Modified dengan `git add .` untuk memindahkan semua file untracked / modified ke dalam staging area</sub>
#### Example :
```
git add .
```

<img src="https://i.ibb.co/VCzzBss/179a1163-44b6-43ab-adb2-736e76013599.jpg" alt="179a1163-44b6-43ab-adb2-736e76013599" border="0">


### • git rm [namafile]
Perintah ini menghapus file yang ada dari direktori kerja Anda.<br>
<sub>gunakan `git status` untuk melihat status file yang sudah di remove,lalu lakukan `git commit -m "commit massage"` agar file terekam perubahanya secara permanen pada repository kalian</sub>
#### Example :
```
git rm file2.html
```

<img src="https://i.ibb.co/NK3drPk/c812f018-8b5e-48d9-80c2-ec304802e36f.jpg" alt="c812f018-8b5e-48d9-80c2-ec304802e36f" border="0">


### • git commit -m “[commit message]”
Perintah ini merecords atau mensnapshots perubahan secara permanen dalam riwayat versi repositori kalian.<br>
<sub>gunakan `git status` untuk melihat file yang masih berstatus Utracked atau modified kemudian add file yang masih berstatus Untracked / Modified dengan `git add` untuk memindahkan semua file untracked / modified ke dalam staging area,lalu lakukan `git commit`</sub>
#### Example :
```
git commit -m "memodifikasi index.html"
```

<img src="https://i.ibb.co/WDgsM10/b6477930-735e-4461-b0db-d2b7c6264f02.jpg" alt="b6477930-735e-4461-b0db-d2b7c6264f02" border="0">



