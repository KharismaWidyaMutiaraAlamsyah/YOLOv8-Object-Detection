# 🔍 YOLOv8 Object Detection (Tugas Akhir S1 Teknik Informatika)

Implementasi model *Deep Learning* **YOLOv8 (You Only Look Once v8)** berbasis Python dan Google Colab untuk deteksi objek otomatis secara *real-time* sebagai bagian dari penelitian Tugas Akhir (Skripsi) Sarjana Teknik Informatika, Universitas Palangka Raya.

## ✨ Fitur & Alur Eksperimen

* **Preprocessing & Manajemen Dataset:** Pembagian dataset citra (*train*, *validation*, *test*) beserta anotasi label berformat YOLO.
* **Pelatihan Model (Model Training):** Pelatihan arsitektur YOLOv8 menggunakan akselerasi GPU pada lingkungan Google Colaboratory.
* **Evaluasi Performa Model:** Analisis metrik akurasi deteksi meliputi *Precision*, *Recall*, *mAP@50*, dan *Confusion Matrix*.
* **Inferensi & Pengujian Deteksi:** Pengujian deteksi objek pada data citra baru beserta visualisasi *bounding box* dan *confidence score*.

## 🛠️ Teknologi yang Digunakan

* **Bahasa Pemrograman:** Python 3
* **Framework Deep Learning:** Ultralytics YOLOv8, PyTorch
* **Lingkungan Eksekusi:** Google Colaboratory (Jupyter Notebook `.ipynb`)
* **Library Pendukung:** OpenCV, NumPy, Matplotlib

## 📂 Struktur Repositori

* `Yolo_8_FIX.ipynb` — Notebook utama berisi alur lengkap konfigurasi lingkungan, pelatihan model, evaluasi metrik, hingga pengujian deteksi.
