# ZaraSalesAnalysis
## 1. Deskripsi Dataset
Dataset ini berisi data penjualan produk Zara dan mencakup berbagai informasi terkait produk yang dijual, promosi, kategori produk, dan detail penjualan lainnya. Berikut adalah penjelasan untuk setiap kolom dalam dataset:

- Product ID: Unique identifier for each product.
        Deskripsi: ID unik yang digunakan untuk mengidentifikasi setiap produk secara individual.

- Product Position: The position of the product in the catalog or store layout.
        Deskripsi: Posisi produk dalam katalog atau tata letak toko, seperti lorong (aisle), ujung lorong (end-cap), atau depan toko (front of store).

- Promotion: Indicator of whether the product is currently on promotion or not.
        Deskripsi: Indikator yang menunjukkan apakah produk sedang dalam promosi atau tidak. Nilai mungkin termasuk 'Yes' untuk produk yang dipromosikan dan 'No' untuk produk yang tidak dipromosikan.

- Product Category: The category of the product, such as clothing, accessories, shoes, etc.
        Deskripsi: Kategori produk, seperti pakaian, aksesoris, sepatu, dll.

- Seasonal: Indicator of whether the product is part of a specific seasonal collection.
        Deskripsi: Indikator yang menunjukkan apakah produk merupakan bagian dari koleksi musiman tertentu. Nilai mungkin termasuk 'Yes' untuk produk musiman dan 'No' untuk produk non-musiman.

- Sales Volume: The quantity of products sold.
        Deskripsi: Jumlah produk yang terjual.

- Brand: Brand of the product.
        Deskripsi: Merek produk.

- URL: Product URL (e.g., if the product is sold online).
        Deskripsi: URL produk, jika produk dijual secara online.

- SKU: Stock Keeping Unit, a unique code used to identify items available for sale.
        Deskripsi: Kode unik yang digunakan untuk mengidentifikasi item yang tersedia untuk dijual.

- Name: Name of the product.
        Deskripsi: Nama produk.

- Description: Description of the product.
        Deskripsi: Deskripsi produk.

- Price: Price of the product.
        Deskripsi: Harga produk.

- Currency: Currency of the product price.
        Deskripsi: Mata uang dari harga produk.

- Scraped_at: The time when the data was scraped (e.g., in web scraping process).
        Deskripsi: Waktu saat data diambil (misalnya, dalam proses web scraping).

- Terms: Terms or conditions of the product.
        Deskripsi: Syarat atau kondisi dari produk.

- Section: Section or category where the product is sold in the store (e.g., women's clothing, men's clothing, children's clothing, etc.).

## 2.Data Cleaning
Dataset penjualan Zara telah melalui proses pembersihan data untuk memastikan keakuratan dan konsistensi analisis. Berikut adalah langkah-langkah yang telah dilakukan:

- Menghapus Data Duplikat:
        Data duplikat diidentifikasi dan dihapus untuk memastikan bahwa setiap entri unik. Ini membantu mencegah bias dalam analisis penjualan.
  
- Mengubah Format Data:
        Kolom tanggal diformat sebagai tanggal, kolom numerik diformat sebagai angka atau mata uang, dan kolom kategori diformat sebagai teks. Perubahan ini dilakukan untuk memastikan bahwa setiap kolom memiliki format data yang tepat.
  
- Validasi Data:
        Aturan validasi data diterapkan untuk memastikan bahwa data yang dimasukkan di masa depan sesuai dengan kriteria yang ditetapkan. Ini termasuk validasi format angka, tanggal, dan teks untuk mencegah kesalahan input.

Hasil Pembersihan Data

Proses pembersihan data ini menghasilkan dataset yang lebih bersih dan siap untuk analisis lebih lanjut. Langkah-langkah ini memastikan bahwa data penjualan Zara akurat, konsisten, dan dapat diandalkan untuk mendukung pengambilan keputusan bisnis yang lebih baik.

## 3. pertanyaan/permasalahan
1. Apakah produk yang dipromosikan oleh Zara memiliki tingkat penjualan yang lebih tinggi?
2. Jenis pakaian apa yang paling banyak dibeli oleh pelanggan Zara?
3. Apakah konsumen Zara lebih cenderung pada produk untuk pria atau wanita?
4. Di mana posisi produk dengan penjualan tertinggi di toko Zara?
5. Berapa rentang harga yang paling sering dipilih oleh pelanggan Zara?
6. Bagaimana penjualan produk musiman dibandingkan dengan produk non-musiman di Zara?

   
## 4. Insight dan Kesimpulan

**Analisis Penjualan Berdasarkan Promosi**

Produk yang tidak dipromosikan memiliki volume penjualan yang lebih tinggi (200,943 unit) dibandingkan dengan produk yang dipromosikan (194,905 unit). Meskipun promosi menunjukkan peningkatan penjualan, ternyata volume penjualan produk tanpa promosi masih lebih tinggi. Ini menunjukkan bahwa sementara promosi dapat membantu meningkatkan penjualan, produk yang tidak dipromosikan juga memiliki daya tarik yang kuat bagi konsumen. Oleh karena itu, penting untuk memahami faktor-faktor lain yang mempengaruhi penjualan selain promosi, seperti kualitas produk, harga, dan preferensi pelanggan. Memperluas program promosi dan mengidentifikasi waktu yang optimal untuk promosi masih dapat menjadi strategi yang efektif, tetapi harus dikombinasikan dengan upaya lain untuk meningkatkan penjualan.
<br>
<br>
<br>
**Analisis Penjualan Berdasarkan Jenis Pakaian**

Jenis pakaian menunjukkan perbedaan yang signifikan dalam volume penjualan. Jaket memiliki volume penjualan tertinggi (195,744 unit), diikuti oleh jeans dan sepatu. Sweater dan t-shirts memiliki volume penjualan yang lebih rendah dibandingkan jenis pakaian lainnya. Fokus pada produk dengan volume penjualan tinggi seperti jaket dan jeans dapat meningkatkan keuntungan. Strategi untuk meningkatkan penjualan produk dengan volume lebih rendah, seperti promosi atau bundling, juga disarankan.
<br>
<br>
<br>
**Analisis Penjualan Berdasarkan Gender Produk**

Penjualan produk pria (332,475 unit) jauh lebih tinggi dibandingkan dengan produk wanita (63,374 unit). Produk pria menyumbang sekitar 84% dari total penjualan, sedangkan produk wanita hanya menyumbang sekitar 16%. Fokus pada strategi pemasaran dan stok produk pria dapat lebih menguntungkan. Namun, ada potensi untuk meningkatkan penjualan produk wanita melalui kampanye pemasaran yang lebih ditargetkan dan penawaran produk yang lebih beragam.
<br>
<br>
<br>
**Analisis Pengaruh Posisi Barang terhadap Penjualan**

Posisi barang di toko memiliki dampak signifikan terhadap penjualan. Produk yang ditempatkan di lorong (aisle) memiliki volume penjualan tertinggi (152,734 unit), diikuti oleh produk yang ditempatkan di ujung lorong (end-cap) dan di depan toko. Menempatkan produk di lokasi strategis seperti lorong dapat meningkatkan penjualan. Oleh karena itu, evaluasi dan optimisasi tata letak toko secara berkala dapat membantu memaksimalkan penjualan produk.
<br>
<br>
<br>
**Analisis Penjualan Berdasarkan Harga**

Penjualan produk bervariasi berdasarkan harga. Produk dengan harga yang lebih rendah cenderung memiliki volume penjualan yang lebih tinggi. Harga produk berkisar dari $7.99 hingga $119.95 dengan volume penjualan tertinggi di rentang harga yang lebih rendah, seperti $9.99 dan $19.99. Menetapkan harga produk pada rentang yang lebih terjangkau dapat meningkatkan volume penjualan. Disarankan untuk meninjau harga produk secara berkala dan menyesuaikannya dengan preferensi pasar.
<br>
<br>
<br>
**Analisis Penjualan Berdasarkan Musim: Produk Musiman vs Non-Musiman**

Produk musiman memiliki volume penjualan yang lebih tinggi (204,638 unit) dibandingkan dengan produk non-musiman (191,211 unit). Produk musiman menyumbang sekitar 52% dari total penjualan, sementara produk non-musiman menyumbang sekitar 48%. Ini menunjukkan bahwa produk musiman memiliki kinerja penjualan yang lebih baik. Oleh karena itu, strategi untuk meningkatkan stok dan promosi produk musiman pada waktu yang tepat dapat meningkatkan penjualan secara keseluruhan.
<br>
<br>
<br>
**Ringkasan Keseluruhan**

Dari analisis di atas, dapat disimpulkan bahwa produk musiman terbukti efektif dalam meningkatkan volume penjualan. Harga yang lebih terjangkau cenderung menarik lebih banyak pembeli. Penempatan produk di lokasi strategis seperti lorong dapat meningkatkan penjualan. Fokus pada kategori produk yang populer dan kinerja produk berdasarkan gender dapat memaksimalkan keuntungan. Dengan insight dan kesimpulan ini, keputusan yang lebih baik dapat diambil untuk strategi penjualan, penentuan harga, penempatan produk, dan kampanye pemasaran di masa depan.
