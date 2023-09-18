# Testing Data Infrastructure & Analysis
Silahkan mengerjakan sesuai kemampuan Anda, Deadline 18 September 2023, jam 10:00 WIB. Fork repository ini, kirim "Pull Request" jika anda sudah selesai atau kirim email ke royyan@satunol.com.
## Kuis

- [?] Anda memiliki tabel "Orders" dengan kolom-kolom berikut: "OrderID," "CustomerID," "OrderDate," dan "TotalAmount." Tuliskan sebuah kueri SQL untuk menampilkan semua pesanan yang dibuat oleh pelanggan dengan ID tertentu pada tanggal tertentu.
  Jawab:
  SELECT *
  FROM Orders
  WHERE (CustomerID = ...) AND (OrderDate = ...)
  
- [?] Bagaimana Anda akan mengimplementasikan pengolahan data real-time dalam infrastruktur data? Berikan contoh kasus penggunaan di mana pengolahan data real-time sangat penting.
  Jawab:
  Sampai saat ini, perkembangan teknologi bisa menampilkan data real time atau secara langsung dapat dimanfaatkan. Seperci contoh, adanya Google Analytics yang merupakan salah satu 
  tools yang mendukung sistem real time data. Dalam dunia digital marketing, adanya tools ini tentunya sangat membantu para digital marketer bisa langsung melihat bagaimana interaksi 
  yang terjadi di dalam website (baik jumlah maupun asal pengunjung), tanpa perlu menunggu proses pengolahan data.
  
- [?] Mengapa keamanan data sangat penting dalam infrastruktur data? Sebutkan beberapa langkah atau teknik yang dapat digunakan untuk melindungi data yang disimpan dan diproses.
  Jawab:
  Keamanan data sangat penting dalam infrastruktur data karena memperkecil peluang adanya tindakan kriminal. Dengan adanya keamanan data dapat mencegah akses yang tidak diinginkan 
  terhadap komputer, database, maupun website yang oleh oknum-oknum tidak bertanggungjawab. Langkah atau teknik yang dapat digunakan untuk melindungi data yang disimpan dan diproses 
  yaitu membangun infrastruktur IT yang kokoh, melakukan backup data secara berkala, dan memanfaatkan aplikasi atau software antivirus terpercaya untuk mendeteksi ancaman.
  
- [?] Bagaimana Anda akan menangani situasi di mana server database mengalami gangguan atau kegagalan yang mengancam kontinuitas operasional? Jelaskan tindakan darurat yang akan Anda lakukan.
  Jawab:
  Melakukan letak kesalahan terlebih dahulu. Selanjutnya, mengecek info lagin dan pengaturan koneksi atau server database. Lalu, memperbaikinya apabila terjadi kesalahan.
  
- [?] Bagaimana Anda akan merencanakan dan mengembangkan infrastruktur data yang lebih besar untuk mendukung pertumbuhan bisnis? Jelaskan tahapan utama yang akan Anda lakukan.
  Jawab:
  Memanfaatkan teknologi dalam strategi bisnis, menggunakan sosial media dan digital marketing, membuat inovasi dengan membuat produk atau jasa berbeda dari yang lain, dan memberikan 
  pelayanan yang baik kepada konsumen.
  
- [?] Mengapa visualisasi data penting dalam analisis data? Berikan contoh alat atau teknik yang biasa digunakan untuk membuat visualisasi data yang efektif.
  Jawab:
  Visualisasi data penting dalam analisis data karena kebanyakan orang akan lebih mudah memahami sesuatu dari yang dapat dilihat dalam bentuk gambar visual sehingga membuat gambaran 
  visual dari data dapat memudahkan audiens untuk memahami informasi yang ada. Contoh alat atau teknik yang biasa digunakan untuk membuat visualisasi data yang efektif yaitu Tableau, 
  Google Data Studio, Power BI, dan Microsoft Excel.
  
- [?] Jelaskan apa yang anda ketahui tentang: Race Condition, Deadlock, Indexing, Normalization, Replication, Backup and Restore, Data Migration dalam database. Jelaskan juga pengalaman anda yang pernah anda hadapi berhubungan dengan istilah-istilah tersebut.
  Jawab:
  Race Condition adalah situasi di mana beberapa proses mengakses dan memanipulasi data bersama pada saat bersamaan.
  Deadlock adalah keadaan suatu sistem database mempunyai dua transaksi atau lebih, di mana setiap transaksi sedang menunggu suatu item data yang sedang dikunci oleh beberapa transaksi 
  lainnya.
  Indexing adalah sebuah objek dalam sistem database yang dapat mempercepat proses pencarian (query) data.
  Normalization adalah sebuah teknik dalam logical desain sebuah basis data yang mengelompokkan atribut dari suatu relasi sehingga membentuk struktur relasi yang baik (tanpa redudansi 
  atau pengulangan data).
  Replication adalah proses membuat salinan database dan menyimpannya di berbagai tujuan lokal atau cloud.
  Backup adalah menduplikasi atau menyalin data. Sedangkan Restore adalah mengembalikan data maupun sistem sama seperti pada keadaan awalnya.
  Data Migration adalah proses memindahkan data dalam jumlah besar dari satu lokasi ke lokasi lain.
  Pengalaman yang pernah saya hadapi dari beberapa istilah-istilah tersebut saat menggunakan SQL yang mana melakukan Indexing dan Normalization. Selain itu, juga pengalaman saat 
  melakukan Replication, Backup, dan Restore beberapa file di penyimpanan laptop. 

## Alghoritma
Kerjakan dengan menggunakan bahasa pemograman yg anda kuasai, buat folder terpisah untuk soal ini
- [!] Anda memiliki dua buah array, yaitu DATA dan QUERIES, tentukan berapa kali setiap kata dalam QUERIES muncul dalam array DATA. Buatlah sebuah fungsi atau program untuk menghasilkan output yang berisi jumlah kemunculan setiap kata dalam QUERIES dalam DATA. 
Contoh:  
```
DATA = ['aple', 'banana', 'cherry', 'banana', 'apple']
QUERIES = ['apple', 'banana', 'grape']

# Fungsi atau program Anda akan menghasilkan output berupa list, seperti ini:
# [2, 2, 0]

# Penjelasan:
# - Kata 'apple' muncul 2 kali dalam DATA.
# - Kata 'banana' juga muncul 2 kali dalam DATA.
# - Kata 'grape' tidak muncul sama sekali dalam DATA.
```
- [!] Silahkan cari hasil dari pengurangan dari jumlah diagonal sebuah matrik NxN Contoh:

Contoh:
```
Matrix = [[1, 2, 0], [4, 5, 6], [7, 8, 9]]

diagonal pertama = 1 + 5 + 9 = 15 
diagonal kedua = 0 + 5 + 7 = 12 

maka hasilnya adalah 15 - 12 = 3
```

- [!] Dengan menggunakan [Mapbox](https://docs.mapbox.com/help/glossary/mapbox-gl-js/) tambahkan polygon pada peta dengan tiga garis warna yang berbeda. 

![Contoh gambar.](mapbox.jpg)

## Challenge
Rancang solusi untuk mengolah data streaming secara real-time, seperti data sensor dari perangkat IoT. Rinci alat atau teknologi yang akan digunakan, serta langkah-langkah yang akan diambil dalam mengatasi masalah data streaming. Tambahkan link figma atau canva untuk mendukung penjelasan konsep anda dengan gambar flowchart yang baik.
