# Project Title

Wine Quality Prediction

## Objective

The objective of this project is to predict the quality of wine based on its chemical characteristics using machine learning classification models. The analysis applies Random Forest, Stochastic Gradient Descent (SGD), and Support Vector Classifier (SVC) to determine whether a wine is of good or bad quality based on features such as acidity, density, and alcohol content.

## Dataset

The dataset contains wine sample information including chemical properties:

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
- Quality (target variable)

Dataset source: [Wine Quality Dataset – Kaggle](https://www.kaggle.com/datasets/yasserh/wine-quality-dataset)

## Tools and Libraries Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook

## Steps Performed

### 1. Data Loading
Imported the wine quality dataset using Pandas.

### 2. Data Cleaning
- Checked for missing values
- Dropped the `Id` column (non-predictive identifier)
- Handled null values

### 3. Exploratory Data Analysis
- Reviewed dataset shape, info, and descriptive statistics
- Examined distribution of wine quality scores

### 4. Data Visualization

Created:
- Quality Distribution Countplot
- Feature Correlation Heatmap
- Alcohol vs. Quality Barplot
- Feature Importance Barplot (Random Forest)

### 5. Data Preprocessing
- Converted quality to binary label (1 = good if quality ≥ 7, else 0)
- Split data into features (X) and target (y)
- Applied 80/20 train-test split
- Standardized features using StandardScaler

### 6. Model Training

Trained three classifier models:
- Random Forest Classifier
- SGD Classifier (Stochastic Gradient Descent)
- Support Vector Classifier (SVC)

### 7. Model Evaluation

Evaluated each model using:
- Accuracy Score
- Classification Report (precision, recall, F1-score)
- Confusion Matrix

### 8. Sample Prediction
Tested the trained Random Forest model on a sample wine input to predict good or bad quality.

## Key Insights

- Alcohol content and sulphates were among the strongest predictors of wine quality.
- Random Forest outperformed SGD and SVC in overall accuracy.
- The correlation heatmap revealed that volatile acidity negatively correlates with quality.
- Converting quality to a binary label simplified the classification task effectively.

## Outcome

This project improved understanding of:

- Binary classification with real-world data
- Feature scaling and preprocessing pipelines
- Comparing multiple classifier models
- Data visualization for chemical datasets
- Feature importance analysis

## Conclusion

The project successfully predicted wine quality using chemical attributes. Random Forest provided the best performance among the three models. The analysis demonstrates how machine learning can be applied to quality control problems in the food and beverage industry.
