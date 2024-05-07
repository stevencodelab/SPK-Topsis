# SPK-Topsis (In Progress)
Sistem Pendukung Keputusan (SPK) Pemilihan Kamera dengan menggunakan metode Topsis (Technique For Others Reference by Similarity to Ideal Solution) agar menemukan Kamera yang sesuai dengan kriteria dan persyaratan yang telah ditentukan.

# System-Requirements
1. XAMPP Versi 5.6.37
2. Apache/2.4.34 
3. PHPMyadmin 4.8.2
   
Karena project ini di tuliskan menggunakan Php versi di bawah 7 sehingga untuk menjalankan nya harus menggunakan `xampp v5.6` karena akan terjadi error apabila menggunakan versi di atas 7. 
`xampp v5.6` bisa di download melalui link berikut ini : (https://sourceforge.net/projects/xampp/files/XAMPP%20Windows/5.6.40/xampp-windows-x64-5.6.40-1-VC11-installer.exe/download)

# How To Use (Cara Menjalankan) :
1. Download project ini dengan cara clone git (`git clone https://github.com/stevenmorison/SPKTopsis.git`).
2. Masuk pada folder `xampp` pindahkan ke dalam folder `htdocs`.  
3. Buka phpmyadmin (`localhost/phpmyadmin`).
4. Buat database baru dengan nama yang sama (`spk_topsis`).
5. Jika ingin mengubah nama database sesuai dengan keinginan anda, jangan lupa mengubah nama database pada `database-config.php`.
6. Import database (`spk_topsis`) dari folder database, tunggu hingga proses import `database` selesai.
7. Akses website melalui `localhost/spk_topsis/index.php`.

# Login 2 Level (`Admin` & `User`)
1. Administrator (username `admin` password `admin`)
2. Pencari Kamera (username `user` password `user`)

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
   ![Screenshot 2024-05-06 131151](https://github.com/stevenmorison/SPK-Topsis/assets/46344837/7596fd36-a1e0-4d33-be65-bcc83bc35338)
