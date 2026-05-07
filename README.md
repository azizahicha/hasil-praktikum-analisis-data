📊 Laporan Praktikum Analisis Performa Penjualan

Business Question
Pada praktikum ini dilakukan analisis data penjualan untuk menjawab beberapa pertanyaan berikut:

Produk apa yang memiliki harga tinggi tetapi penjualannya rendah? Siapa pelanggan terbaik berdasarkan RFM Analysis? Kategori produk mana yang paling efektif dalam penggunaan anggaran iklan? Apakah anggaran iklan berpengaruh terhadap penjualan? 2. Data Wrangling

Sebelum data dianalisis, dilakukan beberapa tahap pembersihan dan persiapan data, yaitu:

Menghapus data yang memiliki nilai Price_Per_Unit ≤ 0 Mengubah kolom Order_Date menjadi format datetime Mengecek dan menghapus data duplikat Mengelompokkan data berdasarkan kategori produk dan pelanggan Menghitung total penjualan, total quantity, serta total anggaran iklan Membuat data untuk analisis RFM: Recency Frequency Monetary

Tahap ini dilakukan agar data lebih rapi dan mudah dianalisis.

Insights Underperformer Product
Dari visualisasi bar chart terlihat bahwa beberapa produk memiliki harga cukup tinggi, tetapi jumlah penjualannya rendah.

Insight:

Harga yang terlalu tinggi dapat memengaruhi minat pembeli. Beberapa produk perlu dievaluasi kembali, baik dari sisi harga maupun strategi promosinya. Efisiensi Kategori Produk

Berdasarkan heatmap yang dibuat, terlihat bahwa tidak semua kategori dengan anggaran iklan besar menghasilkan penjualan tinggi.

Insight:

Ada kategori yang menghabiskan banyak biaya iklan tetapi hasil penjualannya kurang maksimal. Beberapa kategori justru lebih efektif walaupun menggunakan anggaran yang lebih kecil. RFM Analysis

Analisis RFM digunakan untuk mengetahui pelanggan yang paling aktif dan memberikan kontribusi terbesar.

Insight:

Pelanggan dengan nilai RFM tinggi termasuk pelanggan loyal. Pelanggan tersebut sering melakukan transaksi dan memiliki kontribusi besar terhadap pendapatan perusahaan. Pengaruh Iklan terhadap Penjualan

Hasil analisis menunjukkan bahwa kelompok dengan anggaran iklan lebih tinggi memiliki rata-rata penjualan yang lebih besar.

Insight:

Iklan memiliki pengaruh terhadap peningkatan penjualan. Strategi pemasaran yang tepat dapat membantu meningkatkan keuntungan perusahaan. 4. Recommendation

Beberapa rekomendasi yang dapat diberikan berdasarkan hasil analisis:

Memberikan promo atau penyesuaian harga pada produk yang penjualannya rendah. Mempertahankan pelanggan loyal dengan program reward atau diskon khusus. Mengurangi biaya iklan pada kategori yang kurang efektif. Memfokuskan anggaran iklan pada kategori yang menghasilkan penjualan lebih baik. Melakukan evaluasi penjualan secara berkala agar strategi pemasaran lebih optimal. 5. Kesimpulan

Dari hasil analisis dapat disimpulkan bahwa harga produk, strategi iklan, dan perilaku pelanggan sangat memengaruhi performa penjualan.

Produk dengan harga tinggi tidak selalu menghasilkan penjualan tinggi. Selain itu, penggunaan anggaran iklan yang tepat juga dapat membantu meningkatkan penjualan dan keuntungan perusahaan.

Analisis data seperti ini dapat membantu perusahaan dalam mengambil keputusan bisnis yang lebih efektif.

Cara Menjalankan Program Clone Repository git clone Masuk ke Folder Project cd nama-folder Install Library pip install pandas matplotlib seaborn numpy Jalankan Program python nama_file.py
