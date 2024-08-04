# Analisis Kehandalan Mobil Bekas
1. Deskripsi Proyek
Proyek ini bertujuan untuk mengidentifikasi faktor-faktor yang mempengaruhi kehandalan mobil bekas di Saudi Arabia. Model klasifikasi dibangun untuk memprediksi kehandalan mobil berdasarkan berbagai fitur seperti tipe mobil, merek, jenis transmisi, tahun pembuatan, ukuran mesin, dan jarak tempuh. Keluaran dari model ini adalah prediksi kategori kehandalan mobil: "Reliable" (Dapat Diandalkan), "Unreliable" (Tidak Dapat Diandalkan), dan "Moderate" (Sedang).

2. Struktur Direktori
- data/
data_saudi_used_cars.csv: Dataset mobil bekas yang digunakan dalam analisis.
- notebooks/
FINAL.ipynb: Notebook Jupyter yang berisi seluruh analisis, preprocessing, pelatihan model, dan evaluasi.
- models/
best_svc_model.pkl: Model terbaik yang disimpan menggunakan pickle.

3. Persyaratan
Proyek ini memerlukan beberapa pustaka Python, beberapa contohnya yaitu pandas,numpy,scikit-learn, matplotlib, seaborn.

4. Deskripsi Dataset
Dataset berisi data mobil bekas dengan fitur-fitur berikut:
- Type: Tipe mobil.
- Make: Merek mobil.
- Gear_Type: Jenis transmisi (manual atau otomatis).
- Year: Tahun pembuatan mobil.
- Engine_Size: Ukuran mesin dalam liter.
- Mileage: Jarak tempuh mobil dalam kilometer.
- Negotiable: Apakah harga dapat dinegosiasikan (True/False).
- Price: Harga mobil.
- Reliability: Kategori kehandalan mobil (target).

5. Hasil dan Kesimpulan
- Model terbaik untuk memprediksi kehandalan mobil adalah SVC (Support Vector Classifier) tanpa penggunaan SMOTE.
- Model ini memiliki akurasi 96.47% dan F1-Score 96.46%.
- Fitur-fitur seperti tahun pembuatan, jarak tempuh, dan ukuran mesin memiliki pengaruh signifikan terhadap kehandalan mobil.

6. Pengembangan Selanjutnya
- Penambahan fitur baru seperti sejarah perbaikan dan jumlah pemilik sebelumnya.
- Eksplorasi model lain dan teknik feature engineering untuk meningkatkan akurasi.
- Penerapan model di aplikasi nyata seperti platform penjualan mobil.
