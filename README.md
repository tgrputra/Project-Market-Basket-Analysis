# Market Basket Analysis (Apriori Algorithm)

## Overview
Proyek ini berfokus pada **Market Basket Analysis** (Analisis Keranjang Belanja) menggunakan algoritma **Apriori**. Dalam industri ritel modern, memahami pola pembelian pelanggan dan menemukan kombinasi produk yang sering dibeli secara bersamaan merupakan kunci utama untuk meningkatkan pendapatan melalui strategi penjualan silang (*cross-selling*).

Melalui analisis ini, data transaksi ritel historis diolah untuk menjawab beberapa pertanyaan bisnis utama

* Produk apa saja yang memiliki tingkat asosiasi paling tinggi dan paling sering dibeli secara bersamaan dalam satu kali transaksi?
* Seberapa besar probabilitas seorang pelanggan akan membeli suatu produk jika mereka sudah memasukkan produk spesifik lain ke dalam keranjang belanjanya?
* Pola kombinasi produk mana yang memiliki ikatan korelasi paling kuat (*Lift score* tertinggi) dan bukan sekadar kebetulan semata?

Hasil akhir dari proyek ini berupa daftar aturan asosiasi produk yang telah tervalidasi secara matematis. Klasifikasi pola pembelian ini dapat diimplementasikan secara langsung sebagai landasan data untuk merancang paket promosi kombo (*bundling*), mengoptimalkan tata letak produk pada katalog, serta membangun sistem rekomendasi otomatis di keranjang belanja guna meningkatkan nilai rata-rata pesanan (*Average Order Value*).

## Dataset
Dataset yang digunakan dalam proyek ini merupakan **dataset *dummy*** (data sintetis) (Online Retail Data.csv). Penggunaan data *dummy* ini ditujukan murni untuk keperluan demonstrasi portofolio analitik, tanpa memuat atau melanggar privasi data pelanggan sungguhan. Dataset ini memuat informasi mengenai ID Pesanan, Kode Produk, Nama Produk, Kuantitas, Tanggal Pesanan, Harga, dan ID Pelanggan.

## Key Insights & Business Recommendations
Berdasarkan ekstraksi aturan asosiasi pada matriks keranjang belanja, ditemukan beberapa wawasan dan rekomendasi strategis sebagai berikut

1. Analisis terhadap metrik keterwakilan (*Support*) menunjukkan tingkat popularitas produk **Red Hanging Heart T-light Holder** yang cukup signifikan dengan kehadirannya mencapai 5,9% dari total keseluruhan transaksi ritel.
2. Terdapat probabilitas pembelian beriringan (*Confidence*) yang sangat tinggi pada produk tersebut. Tercatat sebanyak 72% pelanggan yang memutuskan untuk membeli varian merah terbukti turut memasukkan **White Hanging Heart T-light Holder** ke dalam keranjang pesanan yang sama.
3. Hubungan asosisasi antara kedua varian produk ini divalidasi sangat kuat secara matematis melalui nilai *Lift* yang melampaui angka 4. Hal ini mengindikasikan bahwa peluang kedua produk tersebut dibeli secara bersamaan dalam satu transaksi melonjak hingga 4 kali lipat dibandingkan jika keduanya dibeli murni secara kebetulan atau terpisah.
4. Berdasarkan temuan pola pembelian tersebut, inisiatif pemasaran strategis dapat difokuskan pada optimalisasi tata letak katalog (*visual merchandising*), di mana varian warna putih diposisikan berdampingan secara langsung dengan varian warna merah. Pembuatan penawaran paket promosi kombo (*product bundling*) untuk kedua variasi ini juga sangat direkomendasikan guna memastikan konversi penjualan ganda secara otomatis.
