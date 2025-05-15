# Prediksi Pasang Surut Air Laut Menggunakan Recurrent Neural Network - Long Short Term Memory (RNN-LSTM)
### Studi Kasus Stasiun Meteorologi Maritim Tanjung Perak Surabaya

Repository ini berisi dataset, source code, dan dokumentasi penelitian mengenai prediksi pasang surut air laut menggunakan model Recurrent Neural Network - Long Short Term Memory (RNN-LSTM).  
Studi kasus dilakukan di Stasiun Meteorologi Maritim Tanjung Perak Surabaya.  
Penelitian ini diharapkan dapat menjadi referensi bagi akademisi, praktisi, dan siapa pun yang ingin mempelajari penerapan deep learning dalam prediksi data time series, khususnya pasang surut air laut.

---
prediksi-pasang-surut-rnn-lstm/
- README.md
- dataset/
  - per_30_mins_data_tidal_wave_surabaya_for_training.xlsx
- code/
  - model_lstm.ipynb
- skripsi_fmipa_laila_lilik_puspitasari.pdf


---

## 📝 Abstrak

Prediksi pasang surut air laut memiliki peranan penting dalam berbagai aplikasi maritim dan pesisir.  
Penelitian ini menggunakan model Recurrent Neural Network-Long Short-Term Memory (RNN-LSTM) untuk memprediksi fenomena pasang surut air laut menggunakan data dari Stasiun Meteorologi Maritim Tanjung Perak Surabaya.  
Hasil penelitian menunjukkan bahwa model RNN-LSTM mampu memprediksi pasang surut air laut dengan akurasi yang baik, serta mampu memprediksi beberapa bulan ke depan meskipun terdapat penurunan presisi pada prediksi jangka panjang.

**Kata kunci:** RNN-LSTM, pasang surut air laut, prediksi, MSE, MAE.

---

## 📊 Dataset

- Dataset tersedia pada folder `dataset`.
- Data bersumber dari BMKG Stasiun Meteorologi Maritim Tanjung Perak Surabaya.
- Periode data: Januari 2022 - April 2024.
- Resolusi data: per 30 menit.
- Format data: `.csv`.
- **Catatan:** Penggunaan data untuk kepentingan edukasi dan riset.

---

## 💻 Kode Program

- Script Python dan notebook tersedia pada folder `code`.
- Model menggunakan arsitektur Bidirectional LSTM.
- Hyperparameter:
  - Optimizer: Adam
  - Loss function: Huber Loss
  - Metrics: MSE, MAE
- Untuk menjalankan:
  1. Pastikan environment Python (versi >=3.8).
  2. Install library yang dibutuhkan:
     ```bash
     pip install -r requirements.txt
     ```
  3. Jalankan `model_lstm.ipynb` di Google Colab / Jupyter Notebook.

---

## 🔬 Metodologi Singkat

1. Pengumpulan data dari BMKG.
2. Preprocessing (resampling per 30 menit, filling missing data, normalisasi).
3. Pembuatan model Bidirectional RNN-LSTM dan pelatihan.
4. Evaluasi model menggunakan MSE dan MAE.
5. Perbandingan hasil prediksi RNN-LSTM dengan CNN.

---

## 📚 Referensi

- Ban et al., 2023
- Ramadhan et al., 2021
- Terven et al., 2023
- Dan referensi lain dapat dilihat dalam `skripsi_fmipa_laila_lilik_puspitasari`.

---

## ⚠️ Disclaimer

File skripsi yang diunggah di repository ini adalah karya ilmiah pribadi saya sebagai mahasiswa.  
Dokumen ini hanya untuk keperluan edukasi dan referensi non-komersial.  
Semua data yang digunakan bersumber dari BMKG Stasiun Meteorologi Maritim Tanjung Perak Surabaya, dengan tetap mematuhi hak penggunaan data sesuai ketentuan yang berlaku.  

