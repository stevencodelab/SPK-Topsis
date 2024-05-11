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
![image](https://github.com/stevencodelab/SPK-Topsis/assets/46344837/2360cc4a-62e9-46af-b06c-f4eb0fe350e6)

2. Dashboard Page (Administrator & User)
   <> Administrator Login
![image](https://github.com/stevencodelab/SPK-Topsis/assets/46344837/931da65d-f738-43cd-8ebb-2409623bb041)
   <> User Login
![image](https://github.com/stevencodelab/SPK-Topsis/assets/46344837/b24ce142-37a0-44df-abba-8f6bdbf20b81)

4. Kriteria & Keterangan Masing-Masing Kriteria (Administrator Only !!!)
![image](https://github.com/stevencodelab/SPK-Topsis/assets/46344837/3ae7290b-39d6-4155-8ac4-3a81414337ba)

6. Alternatif Page / Data Kamera (Administrator Only !!!)
![image](https://github.com/stevencodelab/SPK-Topsis/assets/46344837/f3755464-c1bf-45b3-aa22-5a5e0e8118c6)

7. Perhitungan TOPSIS (In Progress)

8. Data User (Administrator Only !!!)
