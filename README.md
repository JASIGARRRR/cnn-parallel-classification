- Dataset

Dataset tidak disertakan langsung di repository.
Berikut Link Google Drive Dataset:
https://drive.google.com/drive/folders/1zPxX6_h5_uEX73HmllO0hm8b4Kr9WQl3?usp=sharing

- Struktur Dataset
dataset/
├── train/
│   ├── Tomato__Tomato_YellowLeaf__Curl_Virus/
│   └── Tomato_healthy/
├── validation/
│   ├── Tomato__Tomato_YellowLeaf__Curl_Virus/
│   └── Tomato_healthy/
└── test/
    ├── Tomato__Tomato_YellowLeaf__Curl_Virus/
    └── Tomato_healthy/

- Environment
  Python ≥ 3.9
  TensorFlow ≥ 2.13
  NumPy
  Matplotlib
  Scikit-learn

- Instalasi
  pip install -r requirements.txt

- Makefile
  install:
	pip install -r requirements.txt
  train-serial:
	python src/train_serial.py
  train-parallel:
	python src/train_parallel.py
  evaluate:
	python src/evaluation.py

- Kompilasi & Eksekusi
Training Serial
make train-serial
Training Paralel
make train-parallel

-Evaluasi Model
make evaluate

-Cara Pakai
Unduh dataset dari Google Drive
Susun folder dataset sesuai struktur
Jalankan training serial
Jalankan training paralel
