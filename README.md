# UNP_ML_REGRESSION_PROJECT_SCREEN_TIME_IMPACT_ON_MENTAL_HEALTH_USING_-PYTHON

Screen Time Impact on Mental Health

1. Project Overview

I completed this project as part of my Data Science and Machine Learning Internship with United Network of Professionals (UNP), and it was carried out as a collaborative group project. The main objective was to study the impact of screen time on mental health and predict stress levels using regression techniques.

2. Dataset Description

The dataset contains 100,000 records and 6 attributes, including screen time, social media usage, TikTok usage, sleep hours, and mood score. The target variable is "stress_level", measured on a scale of 1 to 10.

3. Data Cleaning

We checked the dataset for missing values, duplicate records, and data types. There were no missing values, and 1,865 duplicate records were removed, leaving 98,135 records for further analysis.

4. Data Preprocessing

We used Python and Pandas for data preprocessing. Outliers were identified and handled using the Interquartile Range (IQR) method with a 1.5 multiplier to improve data quality.

5. Exploratory Data Analysis (EDA)

We performed exploratory data analysis using histograms, boxplots, scatterplots, and correlation heatmaps. This helped us understand the relationship between screen time, sleep, mood, and stress levels.

6. Feature Selection

The dataset includes five predictor variables: screen time, social media platforms used, TikTok usage, sleep hours, and mood score. These features were used to predict stress levels.

7. Model Building

We implemented six machine learning regression models: Linear Regression, K-Nearest Neighbors, Decision Tree, Random Forest, Gradient Boosting, and Support Vector Regression (SVR).

8. Train-Test Splitting

We tested different train-test split ratios, including 80/20, 75/25, 70/30, and 60/40, to compare model performance under different data distributions.

9. Model Evaluation

We evaluated the models using R² Score, Mean Absolute Error (MAE), Mean Squared Error (MSE), and Root Mean Squared Error (RMSE). Hyperparameter tuning was also performed using GridSearchCV.

10. Artificial Neural Network (ANN)

We developed an Artificial Neural Network using TensorFlow and Keras. The model included two hidden layers with 64 and 32 neurons, using ReLU activation and the Adam optimizer.

11. Model Comparison

We compared the performance of traditional machine learning models with the ANN model. The ANN achieved the best overall result with an R² score of approximately 0.7507 using the 75/25 train-test split.

12. Conclusion

The project helped us understand the relationship between screen time and mental health indicators. The results showed that sleep hours and mood score were important factors associated with stress levels.

GOOGLE COLAB FILE LINK : https://drive.google.com/file/d/13-g26DAFoan1N2WFwG8ItmMTfNup3bYT/view?usp=sharing

PROJECY PRESENTATION FILE LINK : https://docs.google.com/presentation/d/1mxDuUVu87jZk_-QfuFUeLYuyoI57npAd/edit?usp=sharing&ouid=104732682746738709604&rtpof=true&sd=true
