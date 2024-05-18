<div id="badges" align="center">
  <a href="https://www.mysql.com/">
    <img src="https://img.shields.io/badge/mysql-4479A1.svg?style=for-the-badge&logo=mysql&logoColor=white"/>
  </a>
   <a href="https://code.visualstudio.com/">
      <img src="https://img.shields.io/badge/Visual%20Studio%20Code-0078d7.svg?style=for-the-badge&logo=visual-studio-code&logoColor=white"/>  
   </a>
   <a href="#">
      <img src="https://img.shields.io/badge/html5-%23E34F26.svg?style=for-the-badge&logo=html5&logoColor=white"/>
   </a>
   <a href="#">
       <img src="https://img.shields.io/badge/css3-%231572B6.svg?style=for-the-badge&logo=css3&logoColor=white"/>
   </a>
   <a href="https://www.php.net/">
       <img src="https://img.shields.io/badge/php-%23777BB4.svg?style=for-the-badge&logo=php&logoColor=white"/>
   </a>
</div>  
<div id="badges" align="center">
   <a href="https://getbootstrap.com/docs/4.6/getting-started/introduction/">
      <img src="https://img.shields.io/badge/bootstrap-%238511FA.svg?style=for-the-badge&logo=bootstrap&logoColor=white"/>
   </a>
   <a href="https://releases.jquery.com/">
      <img src="https://img.shields.io/badge/jquery-%230769AD.svg?style=for-the-badge&logo=jquery&logoColor=white"/>
   </a>
</div>

# SPK-Topsis (In Progress) Native not Framework
Sistem Pendukung Keputusan (SPK) Pemilihan Kamera dengan menggunakan metode Topsis (Technique For Others Reference by Similarity to Ideal Solution) agar menemukan Kamera yang sesuai dengan kriteria dan persyaratan (Kriteria) yang telah ditentukan.
</br>
<h3 align="center">Hi there 👋, jika ingin Full Source Code + Database </h3>
<br>
<h3 align="center">Hubungi saya 👇</h3>
<div id="badges" align="center">
  <a href="https://wa.link/9e41gw">
    <img src="https://img.shields.io/badge/WhatsApp-25D366?style=for-the-badge&logo=whatsapp&logoColor=white"/>
  </a>
  <a href="https://www.instagram.com/stevenmrsn/">
    <img src="https://img.shields.io/badge/Instagram-%23E4405F.svg?style=for-the-badge&logo=Instagram&logoColor=white"/>
  </a>
</div>

# System-Requirements
1. XAMPP Versi 5.6.40
2. Apache/2.4.34 
3. PHPMyadmin 4.8.2
   
Karena project ini di tuliskan menggunakan Php versi di bawah 7 (PHP Version 5.6.40) sehingga untuk menjalankan nya harus menggunakan xampp dengan versi rendah dan saya menggunakan xampp versi `xampp v5.6.40`. 
`xampp v5.6.40` bisa di download melalui link berikut ini : (https://sourceforge.net/projects/xampp/files/XAMPP%20Windows/5.6.40/xampp-windows-x64-5.6.40-1-VC11-installer.exe/download)

# How To Use (Cara Menjalankan) :
1. Download project ini dengan cara `git clone` (`git clone https://github.com/stevencodelab/SPKTopsis.git`).
2. Masuk pada folder `xampp` pindahkan ke dalam folder `htdocs`.  
3. Buka phpmyadmin (`localhost/phpmyadmin`).
4. Buat database baru dengan nama yang sama (`spk_topsis_kamera`).
5. Jika ingin mengubah nama database sesuai dengan keinginan anda, jangan lupa mengubah nama database pada `database-config.php`.
6. Import database (`spk_topsis_kamera`) dari folder database, tunggu hingga proses import `database` selesai.
7. Akses website melalui `localhost/SpkKameraTopsis/index.php`.

# Login 2 Level (`Admin` & `User`)
1. Administrator       (username `admin` password `admin`)
2. Pencari Kamera/User (username `user` password `user`)

# Feature (Fitur)
-> Administrator (Admin)
1. Fitur Login Ke Dashboard.
2. `Create`, `Read`, `Update` `Delete` Data Kriteria (`Nama Kriteria`, `Atribut`, `Bobot`).
3. `Create`, `Read`, `Update` `Delete` Data Kamera
4. `Create`, `Read`, `Update` `Delete` Data Alternatif
5. `Create`, `Read`, `Update` `Delete` Data Analisis
6. `Read` Hasil Perhitungan TOPSIS
7. `Create` `Read`, `Update` `Delete` Data User.
8. Logout
   
-> User
1. Fitur Login Ke Dashboard.
2. `Read` data pada menu `Perankingan`  
3. `Read` data pada menu `Cari Kriteria` untuk mencari Kamera dengan kriteria yang ada.
4. Logout


# Attachment

1. Login Page
![login-page](https://github.com/stevencodelab/SPK-Topsis/assets/46344837/2e47b7ff-2a24-4763-b90f-8f5fe9f5798d)


2. Dashboard Page (Administrator & User)
   <> Administrator Login
![dashboard-admin](https://github.com/stevencodelab/SPK-Topsis/assets/46344837/64e7842e-b8d7-4e8f-b6d5-b562c76a3991)
   <> User Login
![dashboard-user](https://github.com/stevencodelab/SPK-Topsis/assets/46344837/20bb1d8a-af08-4ffb-bb1d-60af498fbd3a)
   
4. Detail Camera (Administrator Only !!!)
![detail-camera](https://github.com/stevencodelab/SPK-Topsis/assets/46344837/65777865-dd19-4c97-952a-7f274ff5304e)
![tambah-detail](https://github.com/stevencodelab/SPK-Topsis/assets/46344837/fb3a4482-20f8-4844-a586-b0fceb159d61)


6. Alternatif Page / Data Kamera (Administrator Only !!!)
![data-alternatif](https://github.com/stevencodelab/SPK-Topsis/assets/46344837/3b5ef6fd-d7bc-4e7c-b263-fd6ca9b3deec)
![tambah-alternatif](https://github.com/stevencodelab/SPK-Topsis/assets/46344837/7831d112-b457-495e-96c4-68ce58e6d450)

# dan lain nya



<br>
