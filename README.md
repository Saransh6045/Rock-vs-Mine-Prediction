# Rock vs Mine Prediction using Machine Learning

## Problem Statement
To predict whether the object beneath the submarine is a rock or a mine on the basis of the SONAR data signals using machine learning algorithms.

### Backstage story
There is a war going on between two countries. A submarine is going from one country to another one under the sea. As retaliation, the enemy country has put mines in the sea. But, in between the mine, there are rocks too. It is done through the SONAR signals.

## About Dataset
- Source: UCI Machine Learning Repository
- Total samples: 208
- Features: 60 numeric sonar signal attributes
- Target:
  - R → Rock
  - M → Mine

## Technologies Used
- Python
- NumPy
- Pandas
- Matplotlib
- Scikit-learn
- Google Colab

## Model Used
Logistic Regression Model
- Reason: It is a binary classification problem. We have to find whether the given object is a rock or a mine.

## Methadology
1. Data loading and preprocessing
2. Handling missing values
3. Feature-label separation
4. Train-test split with stratification
5. Model training using Logistic Regression
6. Model evaluation using the accuracy score
7. Single-input prediction using a reshaped input

## Results
- Training Accuracy: 82%
- Testing Accuracy: 90%

The reason for the better performance of the model on the unseen data than on the training data is due to the small size of the dataset. Another reason is the value of the random state, which specifies the way the dataset is split into training and testing data, as the testing part has an easier dataset. 
