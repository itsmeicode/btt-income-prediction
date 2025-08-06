# Breakthrough Tech (Cornell Tech): Lab 8a Assignment

## U.S. Census Income Prediction

Predict whether an individual earns more or less than $50K annually using machine learning models trained on the U.S. Census dataset.

---

### About the Project

This project explores binary classification techniques to predict income levels using demographic and work-related features from the U.S. Census dataset. It includes data preprocessing, model training, optimization, and performance evaluation using standard metrics.

---

### Models Used

- **Logistic Regression**
- **Random Forest Classifier**

Both models were optimized using **GridSearchCV** and evaluated on classification accuracy, precision, recall, and **ROC AUC**.

---

### Tools & Libraries

- Python  
- Scikit-learn  
- Pandas  
- NumPy  
- Matplotlib  
- Seaborn  

---

### Dataset

- **Source**: [U.S. Census Dataset](https://ecornell.s3.amazonaws.com/content/BTT_V4/censusData.csv)
- Contains demographic and employment-related attributes for over 32,000 individuals.

---

### Key Features

- Data cleaning and encoding for categorical variables  
- Feature scaling  
- Model tuning via GridSearchCV  
- Evaluation using confusion matrix and ROC curves  
- Comparison of logistic regression and ensemble methods  

---

### Results

- Final models achieved high **ROC AUC** and classification performance  
- Demonstrated tradeoffs between interpretability and accuracy  

