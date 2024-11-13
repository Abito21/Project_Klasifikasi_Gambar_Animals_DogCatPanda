# Submission Dicoding "BelajarPengembang Machine Learning" : Animals Dog vs Cat vs Panda ✨

Repository ini berisikan projek klasifikasi gambar menggunakan dataset animals dog vs cat vs panda dari Kaggle. Berikut link https://www.kaggle.com/datasets/ashishsaxena2209/animal-image-datasetdog-cat-and-panda .

## Instalasi

1. Clone repository ke komputer lokal menggunakan perintah dibawah ini:

   ```shell
   [git clone https://github.com/Abito21/Project_Klasifikasi_Gambar_Animals_DogCatPanda.git](https://github.com/Abito21/Project_Klasifikasi_Gambar_Animals_DogCatPanda.git)
   ```

2. Pastikan memiliki environment Python yang sesuai dan library yang diperlukan. Perintah dibawah dapat digunakan untuk melakukan instalasi library yang dibutuhkan :

   ```shell
   pip install -r dashboard/requirements.txt
   ```

## Setup Environment - Python
```
python -m venv main-ds
main-ds\Scripts\activate
pip install -r requirements.txt

Notebook dikerjakan di Google Collaboratory
a. numpy==1.26.4
b. pandas==2.2.2
c. matplotlib==3.8.0
d. seaborn==0.13.2
e. tensorflow==2.18.0
```

## Setup Environment - Shell/Terminal
```
mkdir Project_Klasifikasi_Gambar_Animals_DogCatPanda
cd Project_Klasifikasi_Gambar_Animals_DogCatPanda
pipenv install
pipenv shell
pip install -r requirements.txt
```

## Struktur Direktori

- **/saved_model**: Direktori berisi konversi model ML dengan ekstensi .pb
- **/tfjs_model**: Direktori berisi konversi model ML dengan ekstensi .json
- **/tflite**: Direktori berisi konversi model ML dengan ekstensi .tflite
- **Proyek_Klasifikasi_Gambar_Animals_DogCatPanda.ipynb**: File yang digunakan untuk melakukan olah data gambar dan klasifikasi gambar dengan mode ML.
