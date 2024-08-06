# Breast Cancer Prediction using Machine Learning

This project involves building and evaluating machine learning models to predict the severity of breast cancer using the Mammographic Masses dataset. The dataset contains various features related to mammographic masses and their corresponding severity.

## Dataset

The dataset used in this project is the Mammographic Masses dataset, which consists of the following columns:

- `BI_RADS`
- `age`
- `shape`
- `margin`
- `density`
- `severity`

The target variable is `severity`, indicating whether the mass is benign or malignant.
## Installation

To run this project, you need to have Python and the following libraries installed:

- numpy
- pandas
- scikit-learn
- tensorflow
- matplotlib

You can install the required libraries using the following command:

```bash
pip install numpy pandas scikit-learn tensorflow matplotlib
```

## Data Preprocessing
The dataset contains missing values represented by ?. These values are handled by replacing them with NaN and then dropping any rows with NaN values. The features are then standardized using StandardScaler

## Model Training and Evaluation

Models Used:

- Bayes Classifier
- Decision Tree
- K-Nearest Neighbor (KNN)
- Logistic Regression
- Neural Network
- Random forest
- Support Vector Machine (SVM)
