# Customer Satisfaction Prediction

This project aims to predict customer satisfaction using machine learning models. We compared several classification models including AdaBoost, Decision Tree, Gradient Boosting, KNN, Logistic Regression, and Random Forest. We used Precision as the evaluation metric to assess the models' performance.

## Data Source
- [Kaggle](https://www.kaggle.com/datasets/teejmahal20/airline-passenger-satisfaction)

## Folder Description
- `dataset` : directory used to store data
- `model`   : berisi beberapa file yang berkaitan dengan pengembangan model dalam proyek. Berikut adalah deskripsi singkat dari masing-masing file tersebut:
  - list_cat_nom.txt: File ini berisi daftar nama kolom kategorikal nominal pada dataset yang telah diidentifikasi oleh tim data science. File ini akan digunakan dalam tahap preprocessing data untuk melakukan transformasi pada kolom-kolom tersebut.
  - list_cat_ord.txt: File ini berisi daftar nama kolom kategorikal ordinal pada dataset yang telah diidentifikasi oleh tim data science. File ini akan digunakan dalam tahap preprocessing data untuk melakukan transformasi pada kolom-kolom tersebut.
  - list_num_col.txt: File ini berisi daftar nama kolom numerik pada dataset yang telah diidentifikasi oleh tim data science. File ini akan digunakan dalam tahap preprocessing data untuk melakukan transformasi pada kolom-kolom tersebut.
  - satisfaction_model.pkl: File ini berisi model machine learning yang telah dilatih dan disimpan dalam format pickle. Model ini akan digunakan dalam tahap prediksi untuk memprediksi kepuasan pelanggan berdasarkan data yang diinputkan.
- `script`  :

## Tools and Libraries Used
- numpy
- pandas
- matplotlib
- seaborn
- pickle
- json
- warnings
- scipy.stats
- sklearn

## Model Comparison and Evaluation
We preprocessed the data using various techniques such as train-test split, column transformation, and scaling. The models were trained using a pipeline and optimized using GridSearchCV. Finally, we evaluated the models using cross-validation and generated a confusion matrix, classification report, and other evaluation metrics.

## Conclusion
Overall, this project demonstrates the effectiveness of various machine learning models in predicting customer satisfaction. If you have any questions or feedback, feel free to contact us. Thank you for visiting our project!


