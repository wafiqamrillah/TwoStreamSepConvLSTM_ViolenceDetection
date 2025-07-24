# Efficient Two-Stream Network for Violence Detection Using Separable Convolutional LSTM
** Zahidul Islam, Mohammad Rukonuzzaman, Raiyan Ahmed, Md. Hasanul Kabir, Moshiur Farazi **

** Pembuat Kode Demo : Ahmad Wafiq Amrillah **

## Penjelasan Singkat
Penelitian ini menjelaskan tentang pengembangan sebuah metode yang efisien dan akurat untuk mendeteksi kekerasan secara otomatis dari rekaman video pengawasan. Ini merupakan bagian dari bidang pengenalan aktivitas manusia dalam Computer Vision.

## Prasyarat
Adapun library yang digunakan pada penelitian ini, antara lain:
* Python 3.7
* Tensorflow 2.5.0
* Scikit-image 0.16.2
* Scipy 1.4.1
* Pandas 1.1.5
* Matplotlib 3.2.2
* OpenCV 4.1.2.30
* Numpy 1.18.5
* Tqdm 4.41.1
* Pillow 8.1.2
* Scikit-learn 0.24.0

## Dataset
Dataset yang digunakan pada penelitian ini adalah :
* [RWF2000](https://github.com/mchengny/RWF2000-Video-Database-for-Violence-Detection). Dataset ini berisi video dari tiga jenis kekerasan, yaitu *violence*, *non-violence* dan *no-violence*. Namun, pada demo ini, dataset tidak dapat digunakan karena dataset tidak dapat di-download.
* [Hockey](https://www.kaggle.com/datasets/yassershrief/hockey-fight-vidoes) (../raw_videos/HockeyFights)
* [Movies](https://academictorrents.com/details/70e0794e2292fc051a13f05ea6f5b6c16f3d3635) (../raw_videos/movies)

Dataset yang diunduh disimpan dengan struktur folder seperti berikut : (Contoh untuk dataset Hockey)
```
📦project_directory
  ┣ 📂raw_videos
    ┣ 📂HockeyFights
```

## Demo
Silahkan jalankan file notebook [Demo.ipynb](https://github.com/wafiqamrillah/TwoStreamSepConvLSTM_ViolenceDetection/blob/master/Demo.ipynb) untuk melihat hasil model yang di-train. Untuk model yang sudah di-train, silahkan unduh [file](https://drive.google.com/drive/folders/1igx-plktW069IgXyWg3H78AKuTg-jCza?usp=sharing), lalu simpan di folder project dengan nama folder *trained_models*.

## Source
Silahkan kunjungi repository original milik penulis [Zahidul Islam](https://github.com/zahid58/TwoStreamSepConvLSTM_ViolenceDetection).