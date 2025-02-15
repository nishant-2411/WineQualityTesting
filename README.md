# WineQualityTesting
# Wine Quality Testing using Random Forest Classifier

## Overview
This project builds a machine learning model to predict the quality of wine using a **Random Forest Classifier**. The dataset contains various physicochemical properties of wine, which are used as features to classify the quality of wine.

## Dataset
The dataset used for this project is the **Wine Quality Dataset** from the UCI Machine Learning Repository. It contains attributes like:
- Fixed acidity
- Volatile acidity
- Citric acid
- Residual sugar
- Chlorides
- Free sulfur dioxide
- Total sulfur dioxide
- Density
- pH
- Sulphates
- Alcohol
- Quality (target variable: integer values from 3 to 9)

## Dependencies
To run this project, install the required Python libraries using:
```bash
pip install numpy pandas scikit-learn matplotlib seaborn
```

## Implementation Steps
1. **Data Preprocessing**
   - Load the dataset using pandas.
   - Handle missing values if any.
   - Normalize or standardize the features if needed.
   
2. **Exploratory Data Analysis (EDA)**
   - Analyze feature distributions.
   - Identify correlations using heatmaps.
   - Visualize the data using histograms and boxplots.
   
3. **Model Training**
   - Split the dataset into training and testing sets.
   - Train the **Random Forest Classifier** on the training set.
   - Optimize hyperparameters using GridSearchCV or RandomizedSearchCV.
   
4. **Evaluation**
   - Calculate accuracy, precision, recall, and F1-score.
   - Plot confusion matrix and ROC curve.
   
## Usage
Run the following script to train and evaluate the model:
```bash
python train_model.py
```

## Results
- The model achieves an accuracy of around **XX%** (based on evaluation).
- Important features influencing wine quality include **alcohol content, sulphates, and volatile acidity**.

## Conclusion
This project successfully predicts wine quality using a **Random Forest Classifier**, demonstrating the importance of feature selection and model tuning for achieving good performance.


