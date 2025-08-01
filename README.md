# Logistic Regression Model Selection

This project demonstrates how to perform **model selection for logistic regression** using Airbnb data, as part of the machine learning life cycle.

## 🧠 Objective
To apply logistic regression to a classification task using Airbnb listing data, and perform model selection using hyperparameter tuning and performance evaluation.

## 🧰 Technologies & Libraries
- Python  
- pandas, numpy  
- matplotlib, seaborn  
- scikit-learn

## 📊 Tasks Completed
- Loaded and explored Airbnb dataset  
- Preprocessed features and target labels  
- Split data using `train_test_split`  
- Built and tuned logistic regression models using GridSearchCV  
- Evaluated model performance using:
  - Accuracy  
  - Confusion matrix  
  - Precision-Recall curve

## 📁 Files
| File | Description |
|------|-------------|
| `logistic-regression-selection.ipynb` | Main notebook implementing model selection |
| `airbnbData_train.csv` | Training dataset used for model evaluation |

## 🏁 Results
The best-performing model was selected based on cross-validation, and results were visualized using precision-recall curves and confusion matrices.
