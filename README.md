# Klasifikasi Citra Tumor Otak Menggunakan K-Nearest Neighbor (K-NN)
Proyek ini merupakan implementasi Machine Learning untuk melakukan klasifikasi citra tumor otak berdasarkan fitur-fitur tekstur digital menggunakan algoritma K-Nearest Neighbor (KNN). Proyek ini mencakup seluruh alur kerja data science, mulai dari pembersihan data, eksplorasi data (EDA), hingga evaluasi model.
<h1>Informasi Dataset</h1>
Dataset yang digunakan terdiri dari 3762 sampel citra. Data telah melalui proses ekstraksi fitur untuk mendapatkan karakteristik unik dari setiap citra.
<li>Jumlah Sampel Normal: 2079.</li>
<li>Jumlah Sampel Tumor: 1683.</li>
Dataset di ambil dari <a href="https://www.kaggle.com/datasets/jakeshbohaju/brain-tumor">https://www.kaggle.com/datasets/jakeshbohaju/brain-tumor</a>  
<h1>Fitur yang Diekstraksi</h1>
Fitur-fitur yang digunakan dalam klasifikasi ini meliputi :
<li>Fitur Orde Pertama: Mean, Variance, Standard Deviation, Skewness, Kurtosis.</li>
<li>Fitur Orde Kedua (Tekstur): Contrast, Energy, ASM, Entropy, Homogeneity, Dissimilarity, Correlation, Coarseness.</li>
<h1>Tahapan Proyek</h1>
<li>Pembersihan Data: Memastikan tidak ada nilai yang hilang/null.</li>
<li>Standardisasi: Menyamakan skala fitur menggunakan StandardScaler.</li>
<li>Eksplorasi Data (EDA): Menganalisis sebaran data melalui Stripplot, Scatterplot, dan Density Plot.</li>
<li>Permodelan: Pelatihan model KNN dengan n_neighbors=5.</li>
<li>Evaluasi: Pengujian model menggunakan Confusion Matrix dan Classification Report</li>
<h1>Hasil dan Evaluasi</h1>
Model berhasil mencapai performa yang sangat stabil:
<li>Akurasi: 98.67%.</li>
<li>Presisi & Recall: Seimbang di angka 0.99.</li>
Confusion Matrix:
<li>True Negative: 412 sampel.</li>
<li>True Positive: 331 sampel.</li>
