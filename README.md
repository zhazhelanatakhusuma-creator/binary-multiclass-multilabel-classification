# binary-multiclass-multilabel-classification
# 📊 Machine Learning Classification: Binary, Multiclass, and Multilabel

![Python](https://img.shields.io/badge/Python-3.12-blue?logo=python)
![Jupyter Notebook](https://img.shields.io/badge/Jupyter-Notebook-orange?logo=jupyter)
![Scikit Learn](https://img.shields.io/badge/Scikit--Learn-Machine%20Learning-orange?logo=scikitlearn)
![Kaggle](https://img.shields.io/badge/Dataset-Kaggle-20BEFF?logo=kaggle)
![Project](https://img.shields.io/badge/Project-Academic%20Project-purple)

## 📌 Deskripsi Proyek

Proyek ini merupakan implementasi dan analisis Machine Learning menggunakan 9 dataset dari Kaggle yang mencakup tiga jenis klasifikasi, yaitu **Binary Classification, Multiclass Classification, dan Multilabel Classification**.

Proyek ini bertujuan untuk memahami perbedaan setiap jenis klasifikasi, melakukan pengolahan data, membangun model Machine Learning, serta mengevaluasi hasil prediksi menggunakan beberapa metrik evaluasi.

## 🎯 Tujuan Proyek

1. Memahami konsep Binary, Multiclass, dan Multilabel Classification.
2. Melakukan preprocessing dan eksplorasi data (EDA).
3. Menerapkan algoritma Machine Learning pada berbagai dataset.
4. Melatih dan menguji model klasifikasi.
5. Mengevaluasi performa model menggunakan metrik yang sesuai.
6. Menampilkan visualisasi hasil analisis dan evaluasi model.

## 📂 Dataset yang Digunakan

Proyek ini menggunakan 9 dataset yang dibagi menjadi tiga kategori klasifikasi.

### A. Binary Classification (Klasifikasi Biner)

Binary Classification merupakan metode klasifikasi yang digunakan untuk mengelompokkan data ke dalam dua kelas.

| No. | Nama Dataset | Sumber Dataset |
|---|---|---|
| 1 | Churn Modelling | [Download di Kaggle](https://www.kaggle.com/datasets/shrutimechlearn/churn-modelling) |
| 2 | Hotel Booking Demand | [Download di Kaggle](https://www.kaggle.com/datasets/jessemostipak/hotel-booking-demand) |
| 3 | Chest X-Ray Images (Pneumonia) | [Download di Kaggle](https://www.kaggle.com/datasets/paultimothymooney/chest-xray-pneumonia) |

### B. Multiclass Classification (Klasifikasi Multikelas)

Multiclass Classification merupakan metode klasifikasi yang digunakan untuk mengelompokkan data ke dalam lebih dari dua kelas.

| No. | Nama Dataset | Sumber Dataset |
|---|---|---|
| 4 | Flowers Recognition | [Download di Kaggle](https://www.kaggle.com/datasets/alxmamaev/flowers-recognition) |
| 5 | Leaf Classification | [Download di Kaggle](https://www.kaggle.com/c/leaf-classification) |
| 6 | Dog Breed Identification | [Download di Kaggle](https://www.kaggle.com/c/dog-breed-identification) |

### C. Multilabel Classification (Klasifikasi Multilabel)

Multilabel Classification merupakan metode klasifikasi yang memungkinkan satu data memiliki lebih dari satu label secara bersamaan.

| No. | Nama Dataset | Sumber Dataset |
|---|---|---|
| 7 | Mechanisms of Action (MoA) Prediction | [Download di Kaggle](https://www.kaggle.com/competitions/lish-moa) |
| 8 | Freesound Audio Tagging 2019 | [Download di Kaggle](https://www.kaggle.com/competitions/freesound-audio-tagging-2019) |
| 9 | iMaterialist Challenge (Fashion) at FGVC5 | [Download di Kaggle](https://www.kaggle.com/c/imaterialist-challenge-fashion-2018) |

**Catatan:** Beberapa dataset merupakan kompetisi Kaggle. Pengguna mungkin perlu login dan menyetujui aturan kompetisi sebelum dapat mengunduh data.

## 🛠️ Tools dan Teknologi

Tools dan library yang digunakan dalam proyek ini:

- Python
- Jupyter Notebook
- Anaconda
- Visual Studio Code
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- OpenCV
- Scikit-image
- TensorFlow (opsional)
- Librosa (opsional)

## ⚙️ Tahapan Machine Learning

Tahapan pengerjaan proyek meliputi:

1. **Data Collecting** – Mengumpulkan dataset dari Kaggle.
2. **Data Loading** – Memuat dataset ke dalam Python.
3. **Data Cleaning** – Membersihkan data dari nilai kosong dan data yang tidak sesuai.
4. **EDA (Exploratory Data Analysis)** – Melakukan eksplorasi dan memahami karakteristik data.
5. **Data Processing** – Melakukan preprocessing dan transformasi data.
6. **Data Splitting** – Membagi data menjadi data training dan testing.
7. **Modelling** – Melatih model Machine Learning.
8. **Evaluation** – Mengevaluasi performa model.
9. **Visualization** – Menampilkan visualisasi hasil klasifikasi.
10. **Conclusion** – Menyusun kesimpulan berdasarkan hasil pengujian.

## 📈 Evaluasi Model

Evaluasi model dilakukan menggunakan beberapa metrik, antara lain:

- Accuracy
- Precision
- Recall
- F1-Score
- Confusion Matrix
- Classification Report
- ROC-AUC (jika sesuai dengan jenis klasifikasi)

Untuk klasifikasi multilabel, evaluasi juga dapat menggunakan metrik seperti Hamming Loss dan Jaccard Score.

## 📁 Struktur Repository

```text
binary-multiclass-multilabel-classification/
│
├── README.md
├── requirements.txt
├── Notebook_Classification_Zhazhe_Lhanata_Khusuma.ipynb
│
└── datasets/
    ├── binary/
    ├── multiclass/
    └── multilabel/
```

**Catatan:** Folder `datasets` digunakan untuk menyimpan dataset yang sudah diunduh dari Kaggle di komputer lokal. Dataset tidak harus diunggah ke repository GitHub.

## 🚀 Cara Menjalankan Proyek

1. Clone repository GitHub:

```bash
git clone https://github.com/zhazhelanatak husuma-creator/binary-multiclass-multilabel-classification.git
```

2. Masuk ke folder proyek:

```bash
cd binary-multiclass-multilabel-classification
```

3. Install library yang dibutuhkan:

```bash
pip install -r requirements.txt
```

4. Download dataset dari tautan Kaggle yang tersedia di atas.

5. Simpan dataset sesuai dengan struktur folder yang dijelaskan dalam notebook.

6. Buka file notebook menggunakan Jupyter Notebook, Anaconda, atau Visual Studio Code.

7. Jalankan setiap cell secara berurutan.

## 👩‍💻 Identitas Pembuat

**Nama:** Zhazhe Lhanata Khusuma

**Program Studi:** Teknik Informatika

**Proyek:** Machine Learning Classification

## 📝 Penutup

Melalui proyek ini, diharapkan dapat memahami penerapan Machine Learning dalam menyelesaikan berbagai permasalahan klasifikasi, baik klasifikasi biner, multikelas, maupun multilabel menggunakan dataset yang berbeda.

---

⭐ **Thank you for visiting this repository!**epository a star!
