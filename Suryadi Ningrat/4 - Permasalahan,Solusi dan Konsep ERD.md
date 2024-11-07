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
