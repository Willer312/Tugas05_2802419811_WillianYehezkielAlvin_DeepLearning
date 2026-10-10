# Tugas 05: Advanced CNNs and Transfer Learning

Nama: Willian Yehezkiel Alvin  
NIM: 2802419811 
Mata Kuliah: Deep Learning

## Ringkasan Project
Repositori ini berisi implementasi eksperimen transfer learning untuk klasifikasi citra dengan data terbatas (~1.000 gambar, 10 kelas Oxford-IIIT Pet) menggunakan PyTorch.

## Struktur Berkas
- `Tugas05_Advanced_CNNs_and_Transfer_Learning.ipynb`: Notebook eksperimen lengkap B1-B5.
- `Laporan_Tugas05.pdf`: Laporan analisis teknis (3-5 halaman).
- `metrics_log.csv`: Catatan log metrik mentah hasil eksperimen.
- `failure_analysis_samples.png`: Gambar hasil analisis sampel misklasifikasi.
- `requirements.txt`: Daftar dependensi library Python.

## Ringkasan Hasil Eksperimen
- B1 (From Scratch): Test Accuracy 36.00% | Macro F1 0.3145
- B2 (Feature Extraction): Test Accuracy 88.67% | Macro F1 0.8883
- B3 (Fine-Tuning): Test Accuracy 92.00% | Macro F1 0.9204 (Model Terbaik)
- B4 (No Augmentation): Test Accuracy 90.00% | Macro F1 0.9009
- B5 (EfficientNet-B0): Test Accuracy 86.67% | Macro F1 0.8658

## Cara Menjalankan Code
1. Clone repositori ini.
2. Install dependensi: `pip install -r requirements.txt`
3. Buka dan jalankan seluruh sel pada `Tugas05_Advanced_CNNs_and_Transfer_Learning.ipynb` menggunakan Google Colab atau Jupyter Notebook.