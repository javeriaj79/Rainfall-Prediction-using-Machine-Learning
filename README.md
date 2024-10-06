# Rainfall Prediction Using Machine Learning

## Table of Contents :
1. [Project Overview](#project-overview)
2. [Dataset](#dataset)
3. [Target](#target)
4. [Preprocessing](#preprocessing)
5. [Models Used](#models-used)
6. [Results](#results)
7. [Contributing](#contributing)
8. [Feedback](#feedback)
   
## Project Overview :
This project aims to predict rainfall based on meteorological data using various machine learning algorithms. Rainfall prediction is crucial for agriculture, water resource management, and disaster preparedness. By analyzing historical weather data, the model identifies patterns and correlations that can indicate future rainfall events. In this project, multiple classifiers such as K-Nearest Neighbors (KNN), Random Forest, Gaussian Naive Bayes, and Support Vector Classifier (SVC) are utilized to assess their effectiveness in predicting rainfall occurrence.

The dataset comprises various weather-related features, including temperature, humidity, and wind speed, with the target variable being whether or not it will rain. The effectiveness of each model is evaluated through metrics such as accuracy, precision, recall, F1-score, and AUC scores. Additionally, confusion matrices provide a visual representation of model performance, highlighting areas for improvement in prediction accuracy.

## Dataset :
The dataset used for this project is a historical weather dataset containing features such as temperature, humidity, and other weather-related factors. The target variable is whether or not rainfall occurs (`rainfall`), represented as binary values (Yes/No). Missing values were handled by replacing them with the mean of the respective columns, and categorical variables were replaced with numeric values (Yes = 1, No = 0).

## Target :
- **Target**: The `rainfall` column, representing whether it will rain or not.

## Preprocessing :
- **Handling Missing Values**: Missing data was replaced with column means for numerical columns.
- **Categorical Values**: Categorical features like `yes` and `no` were replaced with numerical values (1 and 0, respectively).
- **Balancing the Dataset**: The dataset was imbalanced, so oversampling of the minority class was performed using the RandomOverSampler technique to ensure better prediction performance.

## Models Used :
1. **K-Nearest Neighbors (KNN)**
2. **Random Forest Classifier**
3. **Gaussian Naive Bayes**
4. **Support Vector Classifier (SVC)**

## Results :
Each model was trained and evaluated using confusion matrices. Classification reports were generated to evaluate precision, recall, and F1-score.

## Contributing :
Contributions are always welcome! Feel free to fork this repository, and submit a pull request to share your improvements with the community.

## Feedback :
If you have any feedback or suggestions, please reach out via [email](#email).
