# PENGEMBANGAN ALGORITMA WATERSHED UNTUK SEGMENTASI CITRA BUAH LOKAL INDONESIA
"Repositori ini berisi implementasi dari makalah "PENGEMBANGAN ALGORITMA WATERSHED UNTUK SEGMENTASI CITRA BUAH LOKAL INDONESIA" oleh Muhammad Bintang Bahy, Nur Rahmat Dwi Riyanto, dan Muhammad Zain Fawwaz Nuruddin Siswantoro.

## Struktur Direktori
```bash
├── datasets
│   ├── ambarella041.JPG
│   ├── ambarella044.JPG
│   ├── avocado168.JPG
│   ├── labels.json
│   ├── salak002.JPG
│   ├── salak006.JPG
│   ├── salak163.JPG
│   ├── sapodilla041.JPG
│   ├── sapodilla122.JPG
│   ├── sapodilla127.JPG
│   ├── siam_lime082.JPG
│   ├── soursop121.JPG
│   ├── soursop126.JPG
│   ├── soursop130.JPG
│   ├── star_fruit001.JPG
│   ├── star_fruit006.JPG
│   └── star_fruit050.JPG
├── main.ipynb
├── README.md
├── reports
└── requirements.txt
```

## Dataset
Dataset diambil dari University of Surabaya-Indonesia Fruit Image Data Set 3000 (Ubaya-IFDS3000). Anda dapat meminta dataset lengkap kepada pemilik dataset.

### Pemrosesan Dataset
Data yang diambil dari Ubaya-IFDS3000 berupa folder yang berisi 3000 gambar buah. Data tersebut kemudian diolah menggunakan bahasa pemrograman Python untuk menghasilkan dataset berupa folder yang berisi 3000 gambar buah dengan berbagai warna latar belakang. Kami memilih 16 gambar dari 3000 gambar tersebut. Kami melakukan segmentasi manual pada 16 gambar tersebut menggunakan label-studio (https://labelstud.io/). Hasil segmentasi manual tersebut kemudian digunakan sebagai referensi untuk hasil segmentasi dari Improved Watershed Algorithm.

## Improved Watershed Algorithm
![Improved Watershed Algorithm](/images/improved_watershed.png)

## Hasil Segmentasi
![Hasil Segmentasi](/images/segmentation_results.png)