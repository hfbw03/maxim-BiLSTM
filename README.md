# maxim-BiLSTM
Repositori untuk penelitian analisis sentimen menggunakan kombinasi model deep learning _Bidirectional Long Short-Term Memory_ (BiLSTM) dan _word embedding FastText_. Dataset yang digunakan untuk pelatihan dan pengujian terdiri dari 10.000 ulasan pengguna aplikasi Maxim di Google Play Store. Setiap ulasan dilabeli sebagai "positif" atau "negatif".

## Tujuan

The main objectives of this project are as follows:

1. Mengetahui hasil accuracy, precision, recall, dan f1‑score dari model BiLSTM dengan word embedding fastText dalam analisis sentimen ulasan pengguna aplikasi transportasi online Maxim.
2. Mengetahui hasil dari analisis sentimen ulasan pengguna aplikasi transportasi online Maxim.

## Dataset

Penelitian ini menggunakan data sekunder yang diperoleh dari kolom ulasan untuk aplikasi Maxim di Google Play Store. Pengambilan data diperoleh melalui scraping menggunakan package google‑play‑scraper pada Python. Data yang digunakan dalam penelitian ini adalah ulasan pengguna aplikasi Maxim di Indonesia sebanyak 10.000 ulasan yang diambil dari aplikasi Google Play Store dalam rentang waktu 12 Oktober 2024 sampai 30 Oktober 2024.

## Tahap-Tahap
Penelitian ini dilakukan melalui sembilan tahapan utama yang terstruktur secara sistematis. Langkah-langkah yang dilalui mencakup: pengumpulan data, preprocessing data, pelabelan sentimen secara otomatis menggunakan VADER, pembagian data, pembuatan representasi kata menggunakan FastText, perancangan arsitektur model BiLSTM, pelatihan model beserta penyetelan hyperparameter, klasifikasi sentimen pada data uji, serta evaluasi performa model menggunakan metrik evaluasi.

## Dependensi

Kode dibuat dan dijalankan pad Python versi 3.8. Untuk menjalankan kode pada notebook `Maxim_BiLSTM - fastText.ipynb`, beberapa package diperlukan, beberapa diantaranya:

- pandas
- numpy
- seaborn
- re
- pytorch
- matplotlib
- string
- google-play-scraper
- nltk

Untuk daftar komprehensif package beserta versi yang digunakan, bisa dilihat pada ...
