# Prediksi Pasang Surut Air Laut Menggunakan Recurrent Neural Network - Long Short Term Memory (RNN-LSTM)
### Studi Kasus Stasiun Meteorologi Maritim Tanjung Perak Surabaya
Tidal Prediction Using Recurrent Neural Network - Long Short Term Memory (RNN-LSTM): Case Study of Tanjung Perak Maritime Meteorological Station Surabaya

Repository ini berisi dataset, source code, dan dokumentasi penelitian mengenai prediksi pasang surut air laut menggunakan model Recurrent Neural Network - Long Short Term Memory (RNN-LSTM).  
Studi kasus dilakukan di Stasiun Meteorologi Maritim Tanjung Perak Surabaya.  
Penelitian ini diharapkan dapat menjadi referensi bagi akademisi, praktisi, dan siapa pun yang ingin mempelajari penerapan deep learning dalam prediksi data time series, khususnya pasang surut air laut.

This repository contains datasets, source code, and research documentation on tidal prediction using the Recurrent Neural Network - Long Short Term Memory (RNN-LSTM) model.  
The case study was conducted at Tanjung Perak Maritime Meteorological Station Surabaya.  
This research is expected to be a reference for academics, practitioners, and anyone who wants to learn the application of deep learning in predicting time series data, especially tidal wave.


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

## 📝 Abstract

Tidal prediction has an important role in various maritime and coastal applications.  
This research uses the Recurrent Neural Network-Long Short-Term Memory (RNN-LSTM) model to predict tidal phenomena using data from the Tanjung Perak Surabaya Maritime Meteorological Station.  
The results show that the RNN-LSTM model is able to predict tides with good accuracy, and is able to predict several months ahead although there is a decrease in precision in long-term predictions.

**Keywords:** RNN-LSTM, tides, prediction, MSE, MAE.

---

## 📊 Dataset

- Dataset tersedia pada folder `dataset`.
- Data bersumber dari BMKG Stasiun Meteorologi Maritim Tanjung Perak Surabaya.
- Periode data: Januari 2022 - April 2024.
- Resolusi data: per 30 menit.
- Format data: `.xlsx`.
- **Catatan:** Penggunaan data untuk kepentingan edukasi dan riset.

- The dataset is available in the `dataset` folder.
- Data sourced from BMKG Tanjung Perak Maritime Meteorological Station Surabaya.
- Data period: January 2022 - April 2024.
- Data resolution: per 30 minutes.
- Data format: `.xlsx`.
- **Note:** The use of data is for educational and research purposes.

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
  2. Jalankan `model_lstm.ipynb` di Google Colab / Jupyter Notebook.

## 💻 Program Code

- The Python script and notebook are available in the `code` folder.
- The model uses Bidirectional LSTM architecture.
- Hyperparameters:
  - Optimizer: Adam
  - Loss function: Huber Loss
  - Metrics: MSE, MAE
- To run:
  1. Ensure Python environment (version >=3.8).
  2. Run `model_lstm.ipynb` in Google Colab/Jupyter Notebook.
  
---

## 🔬 Metodologi Singkat

1. Pengumpulan data dari BMKG.
2. Preprocessing (resampling per 30 menit, filling missing data, normalisasi).
3. Pembuatan model Bidirectional RNN-LSTM dan pelatihan.
4. Evaluasi model menggunakan MSE dan MAE.
5. Perbandingan hasil prediksi RNN-LSTM dengan CNN.

## 🔬 Brief Methodology

1. Data collection from BMKG.
2. Preprocessing (resampling per 30 minutes, filling missing data, normalization).
3. Bidirectional RNN-LSTM model building and training.
4. Model evaluation using MSE and MAE.
5. Comparison of RNN-LSTM prediction results with CNN.
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

## ⚠️ Disclaimer

The thesis file uploaded in this repository is my personal scientific work as a student.  
This document is for non-commercial educational and reference purposes only.  
All data used is sourced from BMKG Tanjung Perak Maritime Meteorological Station Surabaya, while adhering to the rights to use data in accordance with applicable regulations.
