# Tugas_5

Tugas Praktikum Buat program sederhana yang akan menampilkan daftar nilai mahasiswa, dengan ketentuan

Program dibuat dengan menggunakan Dictionary

Tampilkan menu pilihan: (Tambah Data, Ubah Data, Hapus Data, Tampilkan Data, Cari Data)

Nilai Akhir diambil dari perhitungan 3 komponen nilai (tugas: 30%, uts: 35%, uas: 35%)

Buat flowchart dan penjelasan programnya pada README.md.

Commit dan push repository ke github.

PENJELASAN~~~~~

Mulai

Pertama anda menginputkan data={ }, diisi dengan sesuai kenginan anda, dengan format dictionary

Gunakanlah perulangan While True untuk menampilkan data sebanyak banyaknya

lalu Masukan perintah g = input("(T)ambah, (U)bah, (H)apus, (L)ihat,(C)ari, (K)eluar: "),untuk mendapatkan perintah Tambah, Ubah, Hapus,Lihat,Cari,Keluar.

Untuk menambahkan data gunakan fungsi elif, lalu masukan nama, nim, tugas, uts, uas, nilaiakhir, nilai akhir didapat dari = ((tugas)*30/100+(uts)*35/100+(uas)*35/100)

Lalu jika ingin memilih "lihat" gunakan fungsi 'elif' dan gunakan fungsi 'for x in data.items():' untuk memasukan data kedalam tabel data yang kita inputkan, dengan perintah "l". jika data yang tidak terdaftar = 0

Untuk menampilkan pilihan "hapus"gunakan fungsi 'elif' kemudian gunakan fungsi 'if nama in data.keys():' kemudian fungsi'del.data[nama] jika nama yang kita hapus tidak ada dalam tabel maka gunakan fungsi 'else' untuk menampilkan data tidak ada.

lalu untuk menampilan pilihan "cari"" gunakan fungsi 'elif' kemudian gunakan fungsi if nama in data.keys():' untuk mencari data nama kemudian gunakan fungsi 'else' untuk menampilkan data nama yang kita cari tidak ada.

lalu jika ingin keluar dari program gunakan fungsi 'if' kemudian gunakan fungsi break untuk keluar dari data nilai/menghentikan program

Seleseai

Program___________________________________

![image](https://user-images.githubusercontent.com/115479782/204191473-4aa3118c-fd77-4017-8d2c-80c29d79b277.png)

![image](https://user-images.githubusercontent.com/115479782/204191493-75ee6c39-6beb-4137-9e22-9b36805636f3.png)

![image](https://user-images.githubusercontent.com/115479782/204191541-5435e966-eb10-4492-8e1a-bc44ebeeb5c6.png)

Hasil Program______________________________

![image](https://user-images.githubusercontent.com/115479782/204191693-152de1e9-7525-4818-b82c-467981e7f510.png)

![image](https://user-images.githubusercontent.com/115479782/204191757-39d548e8-9ea0-48a2-a9b9-75982edbd2bf.png)

![image](https://user-images.githubusercontent.com/115479782/204191762-8080c4e4-9b7e-4f27-a588-6bb986ace91c.png)

Flowchart___________________________________

![image](https://user-images.githubusercontent.com/115479782/204192069-41d18b36-98cd-436e-b244-6654c5cbf1ad.png)

Sekian Dari Saya 

Terima Kasih:)
