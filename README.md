# Klasifikasi Kematangan Buah Kopi Menggunakan YOLOv8

Proyek ini digunakan untuk mendeteksi tingkat kematangan buah kopi secara otomatis berdasarkan citra gambar.

## 📌 Informasi Proyek
- *Dataset Source:* [Kaggle - Dataset Coffee Cherry](https://www.kaggle.com/datasets/harisyunanda/dataset-coffee-cherry)
- *Total Data:* ~1.000 Citra Gambar
- *Kelas Deteksi (3 Kelas):*
  1. belum matang (Hijau)
  2. setengah matang (Kuning/Jingga)
  3. matang (Merah)

## 📁 Isi Repositori
- best.pt: Model pembobotan terbaik hasil training YOLOv8.
- confusion_matrix.png: Grafik matriks evaluasi ketepatan model.
- results.png: Grafik evaluasi fungsi loss dan mAP selama training.
