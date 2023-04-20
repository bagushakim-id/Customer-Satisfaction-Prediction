# Customer Satisfaction Prediction

This project aims to predict customer satisfaction using machine learning models. We compared several classification models including AdaBoost, Decision Tree, Gradient Boosting, KNN, Logistic Regression, and Random Forest. We used Precision as the evaluation metric to assess the models' performance.

## Data Source
- [Kaggle](https://www.kaggle.com/datasets/teejmahal20/airline-passenger-satisfaction)

## Folder Description
- `dataset` : directory used to store data
- `model`   : contains a selection of files important to the project's model development. The brief descriptions of each of these files are as follows
  - `list_cat_nom.txt`: contains a list of nominal categorical column names in the dataset. This file will be used in the data preprocessing stage.
  - `list_cat_ord.txt`: contains a list of ordinal categorical column names in the dataset. This file will be used in the data preprocessing stage.
  - `list_num_col.txt`: lists the names of the numeric columns in the dataset. This file will be used in the data preprocessing stage.
  - `satisfaction_model.pkl`: contains machine learning models that have been trained and saved in pickle format. This model will be used in the prediction stage to    predict customer satisfaction based on the input data.
- `script`  : contains the Python notebook files used to run the code in this project. There are two files contained in this folder:
  - `inference-notebook.ipynb`: notebook file used to make inferences on the model that has been trained.
  - `main-notebook.ipynb`: notebook file that contains complete code for processing and analyzing data, training models, and evaluating model performance.

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


