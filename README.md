# Mini Portofolio EDA: Analisis Transaksi Pelanggan

## **Background Problem**

Dalam dunia bisnis ritel yang kompetitif, pemahaman mendalam terhadap perilaku pelanggan merupakan fondasi penting untuk pengambilan keputusan strategis. Namun, data transaksi pelanggan seringkali berjumlah besar dan kompleks, sehingga memerlukan proses analisis yang efektif untuk mengungkap *insight* yang berharga.

**Situation:** Dataset transaksi pelanggan yang besar menyulitkan visualisasi dan analisis langsung menggunakan *dashboard* konvensional dengan keterbatasan memori. Selain itu, data mentah seringkali mengandung ketidaksesuaian seperti *missing values*, duplikat, dan *outlier* yang dapat mengganggu akurasi analisis.

**Task:** Tujuan dari proyek mini portofolio ini adalah untuk melakukan *Exploratory Data Analysis* (EDA) pada dataset transaksi pelanggan untuk memahami karakteristik data, mengidentifikasi dan menangani isu-isu kualitas data, serta mengeksplorasi pola awal yang mungkin relevan. Hasil EDA ini diharapkan dapat memberikan dasar untuk pengembangan strategi bisnis yang lebih terarah.

Mengingat ukuran dataset, file CSV asli dapat diakses melalui tautan berikut: [[link_drive](https://drive.google.com/file/d/1AJZ3O_Rz1iJ8N1ncqqH9VKMX8iwb6rlc/view?usp=sharing)]

## **Version Libraries**
* pandas v2.2.1
* numpy v1.26.4
* matplotlib v3.8.3
* seaborn v0.13.2

## **Insight**

Dari hasil analisis EDA yang telah dilakukan, beberapa *insight* yang diperoleh adalah:

* Distribusi usia pelanggan cenderung mendekati normal dengan kelompok usia tertentu yang lebih dominan.
* Pendapatan tahunan pelanggan terdistribusi relatif normal setelah penanganan *outlier*, dengan sedikit kecenderungan ke pendapatan yang lebih rendah.
* Tidak terdapat korelasi linear yang kuat antara variabel-variabel numerik seperti pendapatan tahunan dan skor pengeluaran.
* Pola frekuensi pembelian dan jumlah transaksi menunjukkan variasi yang signifikan antar pelanggan.
* Setelah penanganan *outlier*, rentang nilai pada fitur-fitur numerik menjadi lebih representatif dari populasi pelanggan secara umum.

## **Advice**

Proyek EDA ini dapat dikembangkan lebih lanjut ke ranah *machine learning* untuk tujuan yang lebih prediktif atau segmentatif:

* **Segmentasi Pelanggan:** Menerapkan algoritma *clustering* (misalnya, K-Means) berdasarkan fitur-fitur perilaku pembelian untuk mengidentifikasi kelompok pelanggan yang berbeda dengan karakteristik unik.
* **Prediksi Nilai Transaksi:** Membangun model regresi untuk memprediksi potensi nilai transaksi pelanggan di masa depan berdasarkan riwayat pembelian dan fitur-fitur lainnya.
* **Analisis RFM (Recency, Frequency, Monetary):** Mengembangkan metrik RFM untuk mengidentifikasi pelanggan berharga dan merancang strategi pemasaran yang ditargetkan.

#EDA #python #DataAnalysis

Anda bisa terhubung dengan saya jika ingin mendiskusikan sesuatu, m.ramdhan.hidayatullah@gmail.com
