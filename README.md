# Kaggle-Competition
## Competition 1

## Competition 2:

**1-Problem Definition:** The project starts with defining the problem statement and goals, which in this case involves analyzing a dataset to predict product ratings.

**2-Data Loading:** The training and testing data are loaded into the environment using Pandas from Google Drive, as the project is being conducted in Google Colab.

**3-Data Exploration and Preprocessing:**

The data is explored to gain insights into its structure, including checking for missing values, understanding data types, and performing descriptive statistics.
Necessary data preprocessing steps are performed, such as converting data types, handling missing values using imputation techniques (SimpleImputer), encoding categorical variables using One-Hot Encoding (get_dummies), and normalizing the data using MinMaxScaler.

**4-Feature Selection:**

Irrelevant columns are dropped based on domain knowledge and analysis to focus on relevant features for model training.
Numerical features are selected for further analysis and modeling.

**5-Model Training and Evaluation:**

Machine learning models such as Decision Tree Classifier, Logistic regression (LR), and XGBoost Classifier are trained on the preprocessed data.
Model performance metrics  will be AUROC as a metric on the predicted probability

**6-Hyperparameter Tuning:**

Grid search ,Random search and bayesen search  are used to tune the hyperparameters of the  Classifiers  better performance.

**7-Model Prediction:**

The trained models are used to make predictions on the test dataset to generate ratings for products.
Saving Prediction Files:

Finally, the predictions are saved into CSV files for further analysis or submission.
