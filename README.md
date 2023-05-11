## TUBES-KSI
# IMPLEMENTASI DAN ANALISIS ALGORITMA NAIVE BAYES DALAM KLASIFIKASI KUALITAS AIR YANG DAPAT DIMINUM

TUGAS BESAR
KAPITA SELEKTA INFORMATIKA (RD)

## KELOMPOK :
- Muhammad Maulana			120140080
- Hanif Putra Agusta		120140120
- Muhammad Hadi Arsa		120140150

## Deskripsi Program
Program ini adalah sebuah implementasi algoritma Naive Bayes dalam klasifikasi kualitas air yang dapat diminum berdasarkan dataset yang diberikan. Program ini menggunakan library Pandas untuk membaca dataset dalam format CSV, kemudian melakukan pemrosesan data untuk menambahkan kolom jenis air berdasarkan nilai pH, menghilangkan baris dengan nilai NaN, dan memisahkan data menjadi data atribut dan data label.
Selanjutnya, program membagi data menjadi data latih dan data uji dengan menggunakan fungsi train_test_split dari library sklearn. Kemudian, program membuat model Naive Bayes dengan menggunakan library GaussianNB dari sklearn dan melatih model dengan data latih.
Setelah model dilatih, program melakukan prediksi pada data uji dan menghitung akurasi model dengan menggunakan fungsi accuracy_score dari sklearn. Selain itu, program juga menghitung nilai precision, recall, dan f1-score menggunakan fungsi classification_report dari sklearn.
Hasil output program menampilkan dataset dengan kolom jenis air, jumlah data dari masing-masing jenis air, akurasi model, serta nilai precision, recall, dan f1-score untuk masing-masing kelas.

## Library yang digunakan
- pandas
- sklearn.model_selection/train_test_split
- sklearn.naive_bayes/GaussianNB
- sklearn.metrics/accuracy_score, precision_score, recall_score







