# Klasifikasi Kategori Artikel Sastra.org dengan Doc2Vec dan pemodelan XGBoost

## Deskripsi Singkat
Proyek ini bertujuan untuk mengembangkan model klasifikasi teks pada kumpulan artikel bertema bahasa dan budaya. Model ini memanfaatkan teknologi Doc2Vec untuk representasi teks dan algoritma XGBoost untuk klasifikasi. Proyek ini juga mencakup analisis preprocessing data, pembelajaran, dan evaluasi performa model.

## Screenshot dan Visualisasi
Berikut adalah beberapa visualisasi yang tersedia dalam proyek:

1. **Learning Curve**
![Image](https://github.com/user-attachments/assets/a15d91c5-bad3-4eb8-8341-3db458dac2d2)

2. **Performance Metrics**
![Image](https://github.com/user-attachments/assets/08a10727-95ec-4fc0-8844-88a9c2aab690)

## Teknologi yang Digunakan
- **Python Libraries**:
  - Gensim (Doc2Vec)
  - XGBoost
  - NLTK
  - Sastrawi
  - Scikit-learn
  - Matplotlib & Seaborn

- **Pendekatan Pemrosesan**:
  - Tokenisasi
  - Penghapusan Stopwords
  - Stemming

## Cara Install
Ikuti langkah-langkah di bawah ini untuk menjalankan proyek ini:

1. **Persiapkan Lingkungan Python**:
   - Pastikan Python 3.8 atau versi lebih baru sudah terinstal.
   - Install library yang diperlukan dengan menjalankan perintah berikut:
     ```bash
     pip install --upgrade scikit-learn xgboost sastrawi gensim nltk matplotlib seaborn
     ```

2. **Download Dataset**:
   - Pastikan dataset sudah diunduh dan disimpan di lokasi yang benar.

3. **Clone Repository**:
   - Clone repository proyek ini:
     ```bash
     git clone <repository-link>
     ```

4. **Konfigurasi dan Jalankan Proyek**:
   - Import dataset menggunakan Google Colab atau jalankan secara lokal.
   - Pastikan file dan folder dataset berada pada direktori yang sesuai.
   - Gunakan editor teks seperti Jupyter Notebook untuk menjalankan file proyek.

5. **Jalankan Notebook**:
   - Buka file `.ipynb` menggunakan Jupyter Notebook atau Google Colab.
   - Ikuti langkah-langkah dalam notebook untuk menjalankan preprocessing, pelatihan model, dan evaluasi.

6. **Evaluasi Hasil**:
   - Perhatikan learning curve dan confusion matrix untuk memahami performa model.

## Penjelasan Proyek
Proyek ini melibatkan beberapa tahapan utama:

1. **Preprocessing Data**:
   - Menghapus tanda baca, stopwords, dan tokenisasi teks.
   - Menggunakan algoritma stemming untuk mengembalikan kata ke bentuk dasar.

2. **Representasi Teks**:
   - Memanfaatkan Doc2Vec untuk mengubah teks menjadi vektor numerik.

3. **Pemodelan dan Evaluasi**:
   - Menggunakan XGBoost sebagai model utama untuk klasifikasi.
   - Menampilkan metrik evaluasi seperti accuracy, precision, recall, dan F1-score.

4. **Visualisasi**:
   - Learning curve menggambarkan proses pelatihan.
   - Confusion matrix memberikan insight terhadap prediksi model.

---

Untuk detail lebih lanjut, silakan kunjungi dokumentasi atau file notebook terkait. Jangan ragu untuk menghubungi pengembang jika membutuhkan bantuan.

