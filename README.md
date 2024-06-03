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
Sistem Pendukung Keputusan (SPK) Pemilihan Kamera dengan menggunakan metode Topsis (Technique For Others Reference by Similarity to Ideal Solution) agar menemukan Kamera Digital yang sesuai dengan kriteria dan persyaratan (Kriteria) yang telah ditentukan.
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
6. `Read` Hasil Perhitungan TOPSIS :
   a. Matriks Ternormalisasi
   b. Matriks Ternormalisasi Terbobot
   c. Pembagi
   d. Solusi Ideal Positif Negatif (A+ A-)
   e. Jarak Euclidien (D+ D-) Untuk Masing-Masing Alternatif
   f. Preferensi (V)
   g. Ranking
8. `Create` `Read`, `Update` `Delete` Data User.
9. Logout
   
-> User
1. Fitur Login Ke Dashboard.
2. `Read` data pada menu `Perankingan`  
3. `Read` data pada menu `Cari Kriteria` untuk mencari Kamera dengan kriteria yang ada.
4. Logout


# Attachment

1. Login Page
![login](https://github.com/stevencodelab/SPK-Topsis/assets/46344837/ac5976a9-7173-4bb4-b649-401c3e5d7d53)

2. Register Page
![register](https://github.com/stevencodelab/SPK-Topsis/assets/46344837/e91e2ef9-2802-4270-b1f3-cf9e792b57c3)

3. Dashboard Page (Administrator & User)
   <> Administrator Login
![dash-admin](https://github.com/stevencodelab/SPK-Topsis/assets/46344837/db954532-a7e0-4565-a261-1c0a9e0a27d6)
   <> User Login
![user-dash](https://github.com/stevencodelab/SPK-Topsis/assets/46344837/3b78fee3-04c7-492b-9258-8d5fb2df9d45)

4. Data Camera (Administrator Only !!!)
![datakamera](https://github.com/stevencodelab/SPK-Topsis/assets/46344837/a53b338e-eba2-4c7e-8f38-edb973a9abe3)

5. Data Alternatif (Administrator Only !!!)
![datalternatif](https://github.com/stevencodelab/SPK-Topsis/assets/46344837/4b69e6af-469e-4353-9755-9f02a1e3d3bc)

6. Data Kriteria & Bobot (Administrator Only !!!)
![kriteria](https://github.com/stevencodelab/SPK-Topsis/assets/46344837/6aebca26-bc92-43a7-9276-6e6dcbffb81e)

7. Hasil Perhitungan TOPSIS (Administrator Only !!!)
![hasiltopsis](https://github.com/stevencodelab/SPK-Topsis/assets/46344837/5ea33a38-a62b-49ab-8c57-92239d120a7c)

8. Data User (Administrator Only !!!)
![datauser](https://github.com/stevencodelab/SPK-Topsis/assets/46344837/3ac83df5-e426-488f-968c-0a28b93ca497)

9. Ranking Kamera (User Login)
![ranking](https://github.com/stevencodelab/SPK-Topsis/assets/46344837/246976fc-acaa-49bc-802f-d4155600604c)

10.Pencarian Berdasarkan Kriteria (User Login)
![pencarian](https://github.com/stevencodelab/SPK-Topsis/assets/46344837/8a487b4e-6f2e-405b-b027-3f0a0578f705)

<br>
