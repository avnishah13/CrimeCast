Crime Category Prediction 🕵️‍♀️📊
This notebook focuses on predicting crime categories using data from the following [Kaggle competition]([url](https://www.kaggle.com/competitions/crime-cast-forecasting-crime-categories)) - .

📌 Objective
The goal is to classify crime incidents into one of 39 possible categories based on features like location, day of the week, and address.

🛠️ Workflow Overview
- Exploratory Data Analysis (EDA):
  - Used seaborn and matplotlib to visualize distributions across time, location, and crime type.

- Data Cleaning & Feature Engineering:
  - Extracted useful components from timestamps (Hour, Month).
  - Addressed class imbalance using stratified sampling.
  - Dropped unnecessary features and handled missing values.
   
- Encoding & Scaling:
  - Applied LabelEncoder and OneHotEncoder where necessary.
  - Used StandardScaler to normalize numerical features.

- Model Building:
  - Trained multiple classifiers: Logistic Regression, Random Forest, and SGDClassifier.
  - Evaluated using accuracy score and confusion matrix.

- Prediction on New Data:
  - Made predictions based on preprocessed input.

📈 Results
Achieved competitive accuracy across models. The final model was evaluated for robustness on unseen test data.
