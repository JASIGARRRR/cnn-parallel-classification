**Dataset**
Dataset tidak disertakan langsung di repository.
Berikut Link Google Drive Dataset:
https://drive.google.com/drive/folders/1zPxX6_h5_uEX73HmllO0hm8b4Kr9WQl3?usp=sharing

**Struktur Dataset**
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
1. Pastikan Python 3.9 atau lebih baru telah terpasang.
2. Install seluruh library yang dibutuhkan dengan perintah berikut:
    pip install tensorflow numpy matplotlib pandas scikit-learn seaborn
3. Unduh dataset melalui tautan Google Drive yang disediakan dan ekstrak ke dalam folder project.
4. Pastikan struktur folder dataset sesuai dengan yang dijelaskan.
5. Program dapat dijalankan menggunakan Jupyter Notebook atau Google Colab.

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


