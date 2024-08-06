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
## Usage
1. Clone the repository:
   
```bash
git clone https://github.com/danielmfigueredo/MLCourse_codes.git
cd MLCourse_codes
```

2. Navigate to the notebooks directory:

```bash
cd algorithms
```

3. Run the Jupyter Notebook:

```bash
jupyter notebook knn_classifier.ipynb
```

## Data Preprocessing
The dataset contains missing values represented by ?. These values are handled by replacing them with NaN and then dropping any rows with NaN values. The features are then standardized using StandardScaler

## Model Training and Evaluation

Models Used:

- Bayes Classifier: 78%
- Decision Tree: 72%
- K-Nearest Neighbor (KNN): 81%
- Logistic Regression: 78%
- Neural Network: 80%
- Random forest: 77%
- Support Vector Machine (SVM): 78%
