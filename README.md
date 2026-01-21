- Dataset

Dataset tidak disertakan langsung di repository.
Berikut Link Google Drive Dataset:
https://drive.google.com/drive/folders/1zPxX6_h5_uEX73HmllO0hm8b4Kr9WQl3?usp=sharing

- Struktur Dataset
Leaf_Dataset/
├── Training_Data/
│   ├── Tomato_healthy/                           
│   └── Tomato__Tomato_YellowLeaf__Curl_Virus/
├── Validation_Data/
│   ├── Tomato_healthy/         
│   └── Tomato__Tomato_YellowLeaf__Curl_Virus/
└── Testing_Data/
    ├── Tomato_healthy/     
    └── Tomato__Tomato_YellowLeaf__Curl_Virus/

  **Environment**
  - Python ≥ 3.9
  - TensorFlow ≥ 2.13
  - NumPy
  - Matplotlib
  - Scikit-learn

**Petunjuk Instalasi**
  pip install -r requirements.txt

**Cara Pakai/Langkah Ekseskusi** 
1.	Buka Google Colab
2.	Upload atau buka notebook cnn_paralel_classification.ipynb
3.	Mount/Koneksikan Google Drive:
	from google.colab import drive
	drive.mount('/content/drive')
4.	Set runtime:
    - Jenis runtime : python
    - Akselerator Hardware : GPU
    - Versi Runtime : disarankan/direkomendasikan menggunakan versi yang terbaru.
5.	Jalankan seluruh cell secara berurutan

