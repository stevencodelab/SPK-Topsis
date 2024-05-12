# SPK-Topsis (In Progress) Native not Framework
Sistem Pendukung Keputusan (SPK) Pemilihan Kamera dengan menggunakan metode Topsis (Technique For Others Reference by Similarity to Ideal Solution) agar menemukan Kamera yang sesuai dengan kriteria dan persyaratan yang telah ditentukan.

# System-Requirements
1. XAMPP Versi 5.6.40
2. Apache/2.4.34 
3. PHPMyadmin 4.8.2
   
Karena project ini di tuliskan menggunakan Php versi di bawah 7 sehingga untuk menjalankan nya harus menggunakan xampp versi di bawah 7 dan saya menggunakan xampp versi `xampp v5.6.40`. 
`xampp v5.6.40` bisa di download melalui link berikut ini : (https://sourceforge.net/projects/xampp/files/XAMPP%20Windows/5.6.40/xampp-windows-x64-5.6.40-1-VC11-installer.exe/download)

# How To Use (Cara Menjalankan) :
1. Download project ini dengan cara clone git (`git clone https://github.com/stevenmorison/SPKTopsis.git`).
2. Masuk pada folder `xampp` pindahkan ke dalam folder `htdocs`.  
3. Buka phpmyadmin (`localhost/phpmyadmin`).
4. Buat database baru dengan nama yang sama (`spk_topsis`).
5. Jika ingin mengubah nama database sesuai dengan keinginan anda, jangan lupa mengubah nama database pada `database-config.php`.
6. Import database (`spk_topsis`) dari folder database, tunggu hingga proses import `database` selesai.
7. Akses website melalui `localhost/spk_topsis/index.php`.

# Login 2 Level (`Admin` & `User`)
1. Administrator       (username `admin` password `admin`)
2. Pencari Kamera/User (username `user` password `user`)

# Feature (Fitur)
-> Administrator (Admin)
1. Fitur Login Ke Dashboard.
2. `Create`, `Read`, `Update` `Delete` Data Kriteria (`Nama Kriteria`, `Atribut`, `Bobot`).
3. `Create`, `Read`, `Update` `Delete` Keterangan untuk masing-masing Kriteria.
4. Mengakses Hasil Perhitungan TOPSIS
5. `Read`, `Update` `Delete` Data User.
6. Logout
   
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
