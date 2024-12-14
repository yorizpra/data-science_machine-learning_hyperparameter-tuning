# Data Science Machine Learning Hyperparameter Tuning

Repository ini berisi latihan untuk melakukan hyperparameter tuning pada model machine learning menggunakan berbagai metode seperti Grid Search, Random Search, dan Bayesian Optimization.

## Persyaratan

Pastikan Anda memiliki Python 3.9 dan paket-paket berikut terinstal:

- scikit-learn
- numpy
- pandas
- matplotlib
- scikit-optimize

Anda dapat menginstal semua paket yang diperlukan dengan menjalankan:


pip install -r requirements.txt

## Cara Menggunakan
1. Clone repository ini:
```sh
git clone https://github.com/yorizpra/data-science_machine-learning_hyperparameter-tuning.git
cd data-science_machine-learning_hyperparameter-tuning
```
2. Buka file hyperparameter_tuning.ipynb menggunakan Jupyter Notebook atau JupyterLab:
```sh
jupyter notebook [hyperparameter_tuning.ipynb](http://_vscodecontentref_/1)
```
3. Ikuti langkah-langkah dalam notebook untuk melakukan hyperparameter tuning pada model machine learning.

## Deskripsi Notebook

Notebook ini terdiri dari dua bagian utama:

1. **Latihan Regresi**:
    - Menggunakan dataset `fetch_california_housing` dari Scikit-learn.
    - Melakukan hyperparameter tuning pada model `RandomForestRegressor` menggunakan Grid Search, Random Search, dan Bayesian Optimization.
    - Membandingkan performa dan efisiensi dari ketiga metode tersebut.

2. **Latihan Klasifikasi**:
    - Menggunakan dataset `German Credit` dari OpenML.
    - Melakukan hyperparameter tuning pada model `RandomForestClassifier` menggunakan Grid Search, Random Search, dan Bayesian Optimization.
    - Membandingkan performa dan efisiensi dari ketiga metode tersebut.

## Kesimpulan
- Grid Search memberikan hasil optimal tetapi membutuhkan waktu komputasi yang lebih lama.
- Random Search memberikan hasil yang baik dengan waktu komputasi yang lebih cepat, tetapi bisa saja kehilangan kombinasi hyperparameter yang optimal.
- Bayesian Optimization memberikan keseimbangan terbaik antara efisiensi komputasi dan hasil optimal.

## Catatan
Penurunan akurasi setelah hyperparameter tuning adalah hal yang umum terjadi dalam pembangunan model machine learning. Beberapa faktor yang berkontribusi terhadap masalah ini antara lain overfitting, underfitting, pemilihan ruang pencarian yang tidak tepat, dan evaluasi yang tidak konsisten.