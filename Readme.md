# CNN vs Transfer Learning untuk Klasifikasi Citra

Proyek ini merupakan eksperimen perbandingan antara membangun model **Convolutional Neural Network (CNN) dari awal (from scratch)** dan menggunakan pendekatan **Transfer Learning (MobileNetV2)** untuk tugas klasifikasi citra dua kelas.

## 📌 Deskripsi Proyek
Eksperimen ini bertujuan untuk mengevaluasi performa, waktu pelatihan, dan efisiensi arsitektur dari dua pendekatan *Deep Learning* yang berbeda. 
* **Model 1 (CNN from Scratch):** Dibangun menggunakan arsitektur konvolusi kustom untuk mengklasifikasikan kelas 'Airplane' dan 'Automobile' dari dataset CIFAR-10.
* **Model 2 (Transfer Learning):** Menggunakan *pretrained model* MobileNetV2 dengan strategi *Feature Extraction* untuk mengklasifikasikan gambar 'Cats' dan 'Dogs'.

## 📂 Struktur Direktori
```text
project-cnn-vs-transfer-learning/
├── dataset/               # https://www.kaggle.com/datasets/mmaulanaaryo14/cats-and-dogs-filtered?resource=download
├── notebook/
│   └── cnn_vs_transfer_learning.ipynb
├── report/
│   └── laporan.pdf
├── README.md
└── requirements.txt
