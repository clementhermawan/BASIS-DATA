📊 SQL GROUP BY dan HAVING - Panduan dan Contoh

🔍 Pengantar
Selamat datang di repository ini! Di sini, kami akan membahas tentang penggunaan GROUP BY dan HAVING dalam SQL. Kedua perintah ini sangat penting dalam analisis data dan pengelompokan hasil query berdasarkan kolom tertentu. Repository ini berisi panduan, contoh-contoh kode, serta studi kasus yang akan membantu Anda memahami dan menerapkan GROUP BY dan HAVING secara efektif.

📚 Daftar Isi
Pengantar
Cara Kerja GROUP BY
Menggunakan HAVING untuk Filter Kelompok
Contoh Kode
Studi Kasus
Kontribusi
Lisensi
🚀 Cara Kerja GROUP BY
GROUP BY digunakan untuk mengelompokkan baris data yang memiliki nilai yang sama dalam satu atau lebih kolom. Ini sering digunakan bersama dengan fungsi agregat seperti COUNT, SUM, AVG, MAX, dan MIN untuk meringkas data.

Contoh dasar penggunaan GROUP BY:

sql
Copy code
SELECT department, COUNT(*) as total_employees
FROM employees
GROUP BY department;
Pada contoh di atas, kita mengelompokkan data karyawan berdasarkan departemen dan menghitung jumlah karyawan di setiap departemen.

⚖️ Menggunakan HAVING untuk Filter Kelompok
HAVING digunakan untuk memfilter hasil dari GROUP BY berdasarkan kondisi yang diberikan. Ini sangat mirip dengan WHERE, tetapi WHERE tidak dapat digunakan untuk memfilter hasil fungsi agregat, sehingga HAVING diperlukan.

Contoh penggunaan HAVING:

sql
Copy code
SELECT department, COUNT(*) as total_employees
FROM employees
GROUP BY department
HAVING COUNT(*) > 10;
Di sini, hanya departemen yang memiliki lebih dari 10 karyawan yang akan ditampilkan.

💻 Contoh Kode
Lihat direktori examples untuk melihat berbagai contoh kode yang menggunakan GROUP BY dan HAVING. Contoh-contoh ini meliputi:

Mengelompokkan data penjualan berdasarkan wilayah
Meringkas data inventaris berdasarkan kategori produk
Memfilter transaksi berdasarkan jumlah total
📝 Studi Kasus
Dalam direktori case-studies, Anda akan menemukan studi kasus nyata yang memanfaatkan GROUP BY dan HAVING untuk menyelesaikan masalah bisnis tertentu, seperti:

Menganalisis penjualan tahunan berdasarkan produk
Menentukan kategori produk yang paling banyak terjual
Mengidentifikasi pelanggan dengan transaksi tertinggi
🤝 Kontribusi
Kami sangat menyambut kontribusi dari siapa pun yang tertarik untuk menambah atau memperbaiki konten dalam repository ini. Silakan buka issue atau kirim pull request.

Fork repositori ini.
Buat cabang fitur baru (git checkout -b feature-nama-fitur).
Commit perubahan Anda (git commit -am 'Menambahkan fitur XYZ').
Push ke cabang (git push origin feature-nama-fitur).
Buat Pull Request.
📄 Lisensi
Proyek ini dilisensikan di bawah MIT License. Anda bebas menggunakan, memodifikasi, dan mendistribusikan kode ini dengan menyertakan lisensi yang sama.

Cukup sekian README ini! Kami berharap materi GROUP BY dan HAVING ini bermanfaat bagi Anda. Jika Anda memiliki pertanyaan atau umpan balik, jangan ragu untuk menghubungi kami melalui @kelompok6solid.gmail.com.
