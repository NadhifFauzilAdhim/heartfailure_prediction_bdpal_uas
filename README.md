# Prediksi Risiko Kematian Dini pada Pasien Gagal Jantung Menggunakan Machine Learning

Proyek ini bertujuan untuk mengembangkan model machine learning berbasis PySpark untuk memprediksi risiko kematian dini pada pasien dengan gagal jantung. Dengan menganalisis data klinis, proyek ini memberikan wawasan penting bagi tenaga medis dalam pengambilan keputusan yang lebih baik.

## Latar Belakang
Penyakit kardiovaskular, termasuk gagal jantung, adalah salah satu penyebab utama kematian global. Proyek ini memanfaatkan pendekatan machine learning untuk memproses data kompleks secara efisien dan memberikan prediksi yang lebih akurat dibandingkan metode tradisional.

Dataset mencakup 5000 entri dengan 13 kolom, termasuk informasi klinis, gaya hidup, dan hasil medis. Fitur penting seperti waktu observasi, kadar kreatinin serum, fraksi ejeksi, dan usia diidentifikasi sebagai faktor signifikan dalam memprediksi hasil kesehatan pasien.

## Tujuan
1. Mengembangkan model prediktif untuk risiko kematian dini pada pasien gagal jantung.
2. Mengevaluasi performa model menggunakan metrik seperti ROC-AUC dan akurasi.
3. Menentukan fitur klinis utama yang paling memengaruhi prediksi.

## Alat dan Teknologi
- **Platform**: PySpark
- **Bahasa Pemrograman**: Python
- **Library**:
  - PySpark MLlib
  - Matplotlib, Seaborn untuk visualisasi
  - scikit-learn untuk evaluasi tambahan
- **Model**:
  - Random Forest
  - Gradient Boosted Trees
  - Naive Bayes
  - Decision Tree

## Fitur Model
- **Data Masukan**:
  - Fitur penting meliputi `Ejection_Fraction`, `Serum_Creatinine`, `Time`, `Age`, dan `Serum_Sodium`.
- **Preprocessing**:
  - Normalisasi fitur menggunakan `StandardScaler`.
  - Pembagian dataset menjadi 80% data latih dan 20% data uji.
- **Evaluasi**:
  - Metrik AUC dan akurasi digunakan untuk menilai performa model.
