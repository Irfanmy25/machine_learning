# Capital Bikeshare Customer Prediction Model

## Deskripsi Proyek
Proyek ini bertujuan untuk mengembangkan model machine learning yang dapat memprediksi jumlah penyewa sepeda Capital Bikeshare dalam suatu periode tertentu. Model ini mempertimbangkan berbagai faktor seperti waktu dalam sehari, kondisi cuaca, suhu, dan variasi musiman. Prediksi yang dihasilkan oleh model ini dapat membantu Tim Strategis Bisnis Capital Bikeshare dalam mengelola armada sepeda, perluasan distribusi armada yang sesuai, merencanakan lokasi stasiun, dan memperluas ke area baru.

## Pernyataan Masalah
Tantangan utama adalah memprediksi dengan akurat jumlah pelanggan yang menggunakan layanan sepeda sewa, terutama dalam kondisi cuaca yang bervariasi dan tren musiman. Model prediksi yang akurat akan memungkinkan Capital Bikeshare untuk merencanakan operasi, mengalokasikan sumber daya, dan mengoptimalkan penggunaan sepeda.

## Pendekatan
Pra-pemrosesan Data: Pembersihan data dan ekstrak fitur untuk memastikan data siap untuk dilakukan analisis dan proses modeling.
Pemilihan Model: Saya menggunakan beberapa model regresi, termasuk XGBRegressor() dan RandomForestRegressor(), dan model regresi lainnya.
Tunning Hyperparameter: saya melakukan tunning hyperparameter untuk meningkatkan kinerja best model.
Evaluasi Model: Model dievaluasi berdasarkan skor Mean Absolute Percentage Error (MAPE) dan Mean Absolute Error (MAE).
Model Akhir: Model XGBRegressor() yang sudah dituning menunjukkan kinerja terbaik dan dipilih sebagai model final.

## Metrik Utama
Pada saat dilakukan pengujian pada data test, menghasilkan:
MAPE: ~23% pada data test.
MAE: ~23 pada data test.

Skor Metrik ini menunjukkan bahwa model dapat memprediksi jumlah pelanggan dengan akurasi yang cukup baik, terutama untuk jumlah pelanggan yang lebih tinggi.
