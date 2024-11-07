---
banner: https://files.oaiusercontent.com/file-Iy66HyDjRRM9emGsPGoJ7qf2?se=2024-10-31T01%3A03%3A08Z&sp=r&sv=2024-08-04&sr=b&rscc=max-age%3D604800%2C%20immutable%2C%20private&rscd=attachment%3B%20filename%3D1ebab6aa-55d4-4da4-9474-568002d62786.webp&sig=bYAVKboKllKXx37tXEg%2BVBveaaEPoErKCxLFBP9zwx0%3D
---
# ERD
### **Permasalahan**
1. **Kesulitan Mengelola Data yang Redundan**: Banyak data pelanggan yang berulang seperti nama yang sama (contoh: "Mary Johnson") sehingga menyebabkan kebingungan dalam mengidentifikasi pelanggan.
2. **Potensi Kesalahan dalam Pengiriman**: Informasi yang salah, seperti alamat pengiriman yang berbeda untuk produk yang dibeli oleh pelanggan yang sama, bisa menyebabkan kesalahan pengiriman.
3. **Inefisiensi Pengelolaan Data dalam Spreadsheet**: Spreadsheet tunggal tidak terorganisir, yang menyulitkan untuk mengelola data pelanggan, produk, dan pesanan secara efektif.
### **Solusi**
1. **Pemecahan Data ke dalam Tabel yang Lebih Spesifik**: Memisahkan informasi pelanggan, produk, dan pesanan ke dalam tabel-tabel yang berbeda sesuai fungsinya. Misalnya, ada tabel untuk daftar produk, tabel untuk catatan pesanan, dan tabel pelanggan.
2. **Pembuatan Tabel untuk Konsolidasi Data**: Dengan menggunakan tabel, informasi seperti nama pelanggan dapat diperbarui di satu tempat saja, yang mengurangi redundansi dan memudahkan pengelolaan data.
3. **Penggunaan Entity-Relationship Diagram (ERD)**: ERD digunakan untuk memvisualisasikan hubungan antara tabel yang berbeda dalam basis data, memudahkan identifikasi hubungan dan perbaikan sistem.

### **Konsep ERD**
1. **Entitas**: Setiap tabel diterjemahkan menjadi entitas. Misalnya, tabel Pelanggan, Produk, dan Pesanan merupakan entitas yang terdefinisi dengan atribut masing-masing, seperti nama, alamat, tanggal pembelian, dll.
2. **Atribut**: Setiap entitas memiliki atribut, seperti atribut nama dan alamat pada entitas Pelanggan, atau atribut ID produk dan jumlah stok pada entitas Produk.
3. **Relasi Antar Entitas**: Hubungan antar tabel seperti antara Pelanggan dan Pesanan direpresentasikan oleh garis hubungan dalam ERD, memudahkan visualisasi koneksi antar data.

![[Pasted image 20241024102434.png]]
### **3. Bentuk Pernyataan dalam Video**

1. **Deskripsi tentang Data Redundan**: Video menjelaskan bagaimana data yang berulang dan tidak terorganisir menyebabkan kebingungan, seperti adanya tiga pelanggan bernama Mary Johnson dalam spreadsheet yang sama.
2. **Proses Pembuatan Tabel-Tabel Terpisah**: Video memperlihatkan bagaimana tabel seperti tabel Pelanggan dan tabel Produk dibuat untuk mengelola data secara lebih efisien dan terorganisir.
3. **Pentingnya Penggunaan ERD untuk Memahami Relasi Antar Tabel**: Video menjelaskan bahwa ERD digunakan untuk memvisualisasikan hubungan antar tabel dan memperbaiki sistem agar lebih efisien.

# Lanjutan ERD

### **1. *Kenapa ERD Penting dalam Perancangan Basis Data?*  
   ERD atau Entity Relationship Diagram itu penting karena bisa membantu kita menggambarkan bagaimana struktur data yang akan kita buat. Dengan adanya ERD, kita dapat memahami hubungan antar data secara visual, jadi saat membangun basis data kita bisa menghindari kesalahan yang mungkin terjadi, dan kita juga lebih mudah memahami alur datanya.

#### 2. ***Elemen dan Simbol dalam Perancangan ERD***  
   Dalam membuat ERD, ada beberapa elemen dan simbol utama yang mesti ada, yaitu:
   - *Entitas: Biasanya digambarkan dengan persegi panjang, entitas ini menunjukkan objek utama dalam sistem (misalnya *Siswa atau Guru).
   - *Atribut: Ini adalah karakteristik dari entitas, digambarkan dengan bentuk oval (contoh: *Nama, Alamat untuk entitas Siswa).
   - *Hubungan (Relationship): Hubungan antar entitas ini digambarkan dengan belah ketupat (contoh: hubungan *Mengikuti antara Siswa dan Pelajaran).
   - *Kardinalitas*: Menunjukkan jumlah hubungan antar entitas. Ada yang satu-ke-satu (1:1), satu-ke-banyak (1:N), atau banyak-ke-banyak (M:N).

#### 3. ***Apa yang Dimaksud dengan Entitas dan Contoh Entitasnya***  
   Entitas adalah objek atau hal yang informasinya perlu kita simpan di dalam basis data. Di lingkungan sekitar, contohnya:
   - *Sekolah: Misalnya entitas *Guru, Siswa, Mata Pelajaran, atau Kelas.
   - *Rumah: Contohnya bisa *Anggota Keluarga, Kamar, atau Barang.
   - *Kehidupan Sehari-hari Anak SMK: Bisa berupa *Teman, Tugas, atau Hobi.

#### 4. ***Pengertian Kardinalitas dan Jenisnya***  
   Kardinalitas adalah aturan untuk menunjukkan berapa banyak hubungan yang mungkin ada antara satu entitas dengan entitas lainnya. Jenis-jenis kardinalitas dalam ERD adalah:
   - *One-to-One (1:1): Satu entitas berhubungan dengan satu entitas lainnya saja (misalnya *Siswa dengan NIS).
   - *One-to-Many (1:N): Satu entitas dapat berhubungan dengan banyak entitas lain (contohnya *Guru yang mengajar banyak Siswa).
   - *Many-to-Many (M:N): Banyak entitas yang berhubungan dengan banyak entitas lain (misalnya *Siswa yang mengambil banyak Mata Pelajaran, dan Mata Pelajaran yang diikuti oleh banyak Siswa). 

