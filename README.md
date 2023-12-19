# IMPROVED WATERSHED ALGORITHM FOR IMAGE SEGMENTATION OF LOCAL INDONESIAN FRUIT
This repo contains the implementation of the paper "IMPROVED WATERSHED ALGORITHM FOR IMAGE SEGMENTATION OF LOCAL INDONESIAN FRUIT" by Muhammad Bintang Bahy, Nur Rahmat Dwi Riyanto, and Muhammad Zain Fawwaz Nuruddin Siswantoro.

## Project Structure
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
Dataset was taken from University of Surabaya-Indonesia Fruit Image Data Set 3000 (Ubaya-IFDS3000). Full dataset you can ask to the owner of the dataset.

### Dataset Processing
The data taken from Ubaya-IFDS3000 is in the form of a folder containing 3000 images of fruit. The data is then processed using the python programming language to produce a dataset in the form of a folder containing 3000 images of fruit with a various background color. We picked 16 images from those 3000 images. We do manual segmentation on those 16 images using label-studio (https://labelstud.io/). The result of the manual segmentation is then used as a reference for the segmentation results of the Improved Watershed Algorithm.