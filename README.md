LAPORAN TUGAS
MATA KULIAH PEMROGRAMAN API	

![image](https://github.com/anispp/Pemrograman-API_Kelompok-5/assets/120777302/92161059-a0a0-45f8-9017-f0779b64e4fd)

Disusun oleh: 
Vanessa Aulia Syifa Yudiasmara	(22091397084)
Anis Putri Purwanti			(22091397099)
Danu Teguh Heri Prasetyo		(22091397100)

Dosen Pengampu:
Andi Iwan Nurhidayat, S.Kom., M. T.

PROGRAM STUDI D4 MANAJEMEN INFORMATIKA
FAKULTAS VOKASI
UNIVERSITAS NEGERI SURABAYA
2024

![image](https://github.com/anispp/Pemrograman-API_Kelompok-5/assets/120777302/b5737016-1bfc-43ab-abd6-8e8546e29231)

Membuat database dengan nama “apicrud” yang di dalamnya berisi tabel dengan nama “barang”. Di dalam tabel barang terdapat sejumlah atribut antara lain:
id (int),
nama_barang (varchar),
stok (int),
harga (double).

![image](https://github.com/anispp/Pemrograman-API_Kelompok-5/assets/120777302/cc6f79ab-ad1d-4042-85df-dc7352eca113)

Kode PHP di atas merupakan bagian dari backend untuk operasi CRUD (Create, Read, Update, Delete) pada entitas “barang” dalam database “apicrud”.

![image](https://github.com/anispp/Pemrograman-API_Kelompok-5/assets/120777302/a77d7ce2-e9cf-428d-ae6b-98e5122fbd56)

Program tersebut merupakan bagian dari backend untuk menangani operasi Create (POST) pada entitas “barang” dalam database “apicrud”.

![image](https://github.com/anispp/Pemrograman-API_Kelompok-5/assets/120777302/f0cb4335-0008-4378-ac33-b94510c793fb)

Program tersebut merupakan bagian dari backend untuk menangani operasi Delete (DELETE) pada entitas “barang” dalam database “apicrud”.

![image](https://github.com/anispp/Pemrograman-API_Kelompok-5/assets/120777302/9f5ecfa5-9717-4d68-95ef-3724ca4a8eb2)

Potongan kode program di atas merupakan bagian dari backend untuk menangani operasi Update (PUT) pada entitas “barang” dalam database “apicrud”.

![image](https://github.com/anispp/Pemrograman-API_Kelompok-5/assets/120777302/d4398cf3-9c2e-48fc-bc36-85fe79b11dea)

Cara melihat aplikasi berhasil atau tidak, yakni menggunakan aplikasi ‘postman’. Cara menggunakannya adalah menggunakan parameter GET. Copy link dari local hostnya, lalu di paste ke GET. Sehingga, datanya langsung tertampilkan.

![image](https://github.com/anispp/Pemrograman-API_Kelompok-5/assets/120777302/e7d2f9b2-22be-4fb9-9554-352fa7935f95)

Ubah method menjadi post. Lalu klik body. Memasukkan atribut beserta entitasnya. Kami memasukkan nama barang topi, stok 50, dan harga 10000. 

![image](https://github.com/anispp/Pemrograman-API_Kelompok-5/assets/120777302/c46775e1-5e04-44e6-ba11-3014533a1c0f)

Maka, di localhost akan tampak input terbaru dari aplikasi postman.

![image](https://github.com/anispp/Pemrograman-API_Kelompok-5/assets/120777302/d128a59b-e170-4fd0-89fa-1d953f8a8c33)

Jika ingin menghapus data, ganti request post menjadi delete. Klik params. Misal kita akan mendelete id. Klik id dan value 2.

![image](https://github.com/anispp/Pemrograman-API_Kelompok-5/assets/120777302/d209feb8-73c7-4606-b16d-0b3ccf90896d)

Gambar diatas merupakan hasil dari delete data melalui postman.

![image](https://github.com/anispp/Pemrograman-API_Kelompok-5/assets/120777302/a0f10b0e-4bfd-4a74-93a5-6a214a9861fa)

![image](https://github.com/anispp/Pemrograman-API_Kelompok-5/assets/120777302/59bbe3aa-28b9-43b2-825a-fa1e6f19856b)
