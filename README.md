# Task 16 – Hyperparameter Tuning using GridSearchCV

## 📌 Objective
To optimize a machine learning model using GridSearchCV and compare performance with a default model.

## 📊 Dataset Used
Breast Cancer Dataset (from sklearn)

## 🛠 Tools & Libraries
- Python
- Pandas
- NumPy
- Scikit-learn
- Jupyter Notebook

## ⚙ Steps Performed
1. Loaded dataset using sklearn.
2. Applied preprocessing (feature scaling).
3. Split data into training and testing sets.
4. Trained default SVM model.
5. Defined parameter grid.
6. Applied GridSearchCV with 5-fold cross-validation.
7. Extracted best parameters.
8. Compared performance between default and tuned models.

## 🔍 Best Parameters
Example:
C = 10  
gamma = 0.01  
kernel = rbf  

## 📈 Results
| Model | Accuracy |
|--------|----------|
| Default SVM | 0.96 |
| Tuned SVM | 0.98 |

Tuned model performed better than default model.

## 🎯 Final Outcome
Learned how to optimize models and improve performance using hyperparameter tuning.
