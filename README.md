# scikit-learn CookBook O'Reilly

Repository ini berisi kumpulan materi praktis dan latihan Machine Learning yang diimplementasikan menggunakan Python dan library scikit-learn. Terdapat 13 bab (chapter) yang mencakup seluruh alur kerja machine learning mulai dari persiapan data, pemodelan (supervised & unsupervised), evaluasi model, hingga siap dideploy ke lingkungan produksi.

[Tautan Buku Referensi](https://drive.google.com/file/d/1b7mWwNMYWxOVwnWbPZd8_njVXAgGEMQR/view?usp=sharing)

---

## Daftar Isi & Ringkasan Chapter

Berikut adalah ringkasan umum dari setiap chapter yang ada di dalam repository ini:

### Chapter 01 - Common Conventions and API Elements of scikit-learn
Membahas prinsip dasar desain API scikit-learn seperti Consistency, Simplicity, Modularity, dan Reusability. Chapter ini menjelaskan siklus hidup objek utama scikit-learn:
* **Estimator:** Menggunakan `fit()` untuk belajar dari data dan `predict()` untuk menghasilkan prediksi.
* **Transformer:** Menggunakan `transform()` atau `fit_transform()` untuk manipulasi data (seperti scaling).
* **Pipeline:** Menggabungkan preprocessing dan pemodelan dalam satu workflow otomatis.
* **Hyperparameter Tuning:** Pengantar optimasi model menggunakan `GridSearchCV`.

### Chapter 02 - Pre-Model Workflow and Data Preprocessing
Fokus pada pembersihan dan penyiapan data mentah sebelum dilatih. Topik utama meliputi:
* **Handling Missing Values:** Menggunakan `SimpleImputer`, `KNNImputer`, dan `IterativeImputer`.
* **Feature Scaling:** Standardisasi dan normalisasi data.
* **Categorical Encoding:** One-Hot Encoding dan Ordinal Encoding.
* **Pipeline Integration:** Menyusun preprocessing agar terhindar dari data leakage.

### Chapter 03 - Dimensionality Reduction Techniques
Membahas metode reduksi dimensi untuk mengatasi curse of dimensionality (masalah fitur terlalu banyak) dengan tetap mempertahankan variansi informasi. Teknik yang dipelajari:
* **Principal Component Analysis (PCA):** Reduksi dimensi tanpa pengawasan (unsupervised) berbasis variansi.
* **Linear Discriminant Analysis (LDA):** Reduksi dimensi terawasi (supervised) untuk memaksimalkan keterpisahan antar kelas.
* **t-SNE:** Visualisasi data berdimensi tinggi ke ruang 2D/3D.

### Chapter 04 - Building Models with Distance Metrics and Nearest Neighbors
Mempelajari algoritma klasifikasi berbasis kedekatan jarak, khususnya K-Nearest Neighbors
