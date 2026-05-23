# codealpha_task-1
# Creditworthiness Prediction using Machine Learning

## Project Overview
This project predicts an individual's creditworthiness using Machine Learning techniques. The model analyzes customer financial data and predicts whether a customer is likely to respond positively based on historical information.

## Objective
Build a classification model to predict customer creditworthiness using:
- Data preprocessing
- Feature engineering
- Machine Learning algorithms
- Performance evaluation metrics

## Technologies Used
- Python
- Pandas
- NumPy
- Matplotlib
- Scikit-learn

## Dataset
Dataset used: **Bank Marketing Dataset**

The dataset contains customer details such as:
- Age
- Job
- Marital Status
- Education
- Balance
- Loan Details
- Contact Information
- Customer Response (Target Variable)

## Project Workflow

### 1. Data Extraction
- Extract ZIP dataset file.

### 2. Data Loading
- Load dataset using Pandas.

### 3. Data Preprocessing
- Handle missing values.
- Replace unknown values.
- Numerical missing values filled using mean.
- Categorical missing values filled using mode.

### 4. Data Encoding
- Convert categorical data into numerical format using Label Encoding.

### 5. Feature Selection
- Separate Features (X) and Target Variable (y).

### 6. Train-Test Split
- Split dataset into training and testing sets.

### 7. Model Training
- Use **Random Forest Classifier** for training.

### 8. Prediction
- Predict outcomes using trained model.

### 9. Model Evaluation
Performance metrics used:
- Accuracy Score
- Precision Score
- Recall Score
- F1 Score
- ROC-AUC Score
- Confusion Matrix
- Classification Report

### 10. Visualization
- ROC Curve
- Feature Importance Graph

## Machine Learning Algorithm
**Random Forest Classifier**

Reason for choosing:
- High accuracy
- Handles large datasets efficiently
- Works well with categorical and numerical data

## How to Run the Project

1. Install required libraries:
```bash
pip install pandas numpy matplotlib scikit-learn
```

2. Place dataset ZIP file in project folder.

3. Run the Python file or Jupyter Notebook.

## Output
The project generates:
- Model accuracy scores
- Classification report
- Confusion matrix
- ROC curve visualization
- Feature importance chart

## Future Improvements
- Hyperparameter tuning
- Cross-validation
- Use advanced models like XGBoost or LightGBM
- Deploy model using Flask or Streamlit
