# **Medical Insurance Cost Prediction Project**

This project aims to predict individual medical insurance costs using various features such as age, sex, BMI, number of children, smoking status, and region. The dataset is based on publicly available data that has been cleaned and formatted for analysis.

**Steps Involved:**

1. Data Collection:

   * Loaded the dataset into a Pandas DataFrame for analysis.

2. Data Analysis and Visualization:

    * Explored the dataset to understand its structure and distribution of features.
   * Visualized the distributions of age, sex, BMI, number of children, smoking status, region, and charges using Seaborn and Matplotlib.

3. Data Preprocessing:

    * Checked for and handled missing values.
   * Encoded categorical features (sex, smoker, region) using LabelEncoder.
   * Calculated correlations between features to understand their relationships with insurance charges.
   * Split the data into features and target (charges).

4. Model Selection:


   * Evaluated multiple models (Linear Regression, Lasso, Random Forest Regressor, XGBoost Regressor) using cross-validation and selected the best-performing model based on the mean cross-validation score.

5. Model Training:

    * Split the data into training and testing sets.
   * Trained the selected model (Random Forest Regressor) on the training data.

6. Model Evaluation:

   * Evaluated the model's performance on both training and testing data using R2 score and Mean Absolute Error (MAE).
   * Visualized the comparison between actual and predicted costs for both training and testing data.

7. Predictive System:

   * Implemented a function to predict medical insurance costs for new input data using the trained model.
