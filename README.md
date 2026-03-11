# 🚢 Titanic Survival Prediction — Machine Learning Model Comparison

This project compares multiple machine learning algorithms to predict passenger survival using the Titanic dataset. The goal is to understand how different classification models perform on the same dataset and evaluate their prediction accuracy.

---

# 📊 Models Compared

The following machine learning algorithms were used in this experiment:

- Logistic Regression
- Decision Tree
- Random Forest
- XGBoost

Each model was trained using the same dataset and evaluated using a test dataset to ensure fair comparison.

---

# 🧠 Evaluation Metric

The models were evaluated using **Accuracy**.

Accuracy measures how many predictions were correct out of the total predictions made by the model.

Accuracy Formula:

Accuracy = (True Positives + True Negatives) / (Total Predictions)

Where:

- TP → True Positive  
- TN → True Negative  
- FP → False Positive  
- FN → False Negative  

---

# 📈 Model Performance Results

| Model | Accuracy |
|------|------|
| Logistic Regression | 75.68% |
| Decision Tree | 78.38% |
| Random Forest | 81.08% |
| XGBoost | 70.27% |

---

# 🔎 Observations

## Logistic Regression
Logistic Regression was used as the baseline model. It performs well for simple classification tasks where relationships between features and the target variable are mostly linear.

## Decision Tree
Decision Trees improved the performance compared to Logistic Regression by capturing non-linear relationships between variables.

Example rule learned by the model:

IF Sex = Female → Survived  
IF Sex = Male AND Pclass = 3 → Not Survived

## Random Forest
Random Forest produced the **highest accuracy** in this experiment.

Random Forest is an ensemble learning method that combines multiple decision trees and uses majority voting to improve prediction performance.

Advantages:
- Reduces overfitting
- More stable predictions
- Works well on structured datasets

## XGBoost
XGBoost is a powerful boosting algorithm often used in data science competitions. However, in this experiment, it produced lower accuracy, possibly due to the small dataset size and lack of hyperparameter tuning.

---

# 🏆 Best Performing Model

The best performing model in this experiment was:

**Random Forest — 81.08% Accuracy**

This demonstrates how ensemble models can outperform individual models.

---

# 🛠 Technologies Used

- Python
- Pandas
- NumPy
- Scikit-learn
- XGBoost
- Matplotlib

---

# 📁 Project Workflow

1. Data Loading
2. Data Preprocessing
3. Feature Selection
4. Train-Test Split
5. Model Training
6. Model Evaluation
7. Model Comparison

---

# 📌 Future Improvements

Possible improvements for this project:

- Hyperparameter tuning
- Feature engineering
- Cross-validation
- ROC Curve analysis
- Precision / Recall / F1-score evaluation

---

# 📚 Dataset

Titanic Dataset

This dataset contains passenger information such as:

- Passenger Class
- Sex
- Age
- Fare
- Embarked Port

The goal is to predict whether a passenger survived the Titanic disaster.

---

# ⭐ Conclusion

This project demonstrates how different machine learning algorithms perform on the same classification problem. The results show that ensemble methods like Random Forest can significantly improve predictive performance compared to simpler models.

---
## 📊 Model Comparison

![Model Accuracy](images/model_accuracy.png)

# 👨‍💻 Author

Harindu Dulith  
Undergraduate | Data Science Enthusiast  
University of Colombo# -Titanic-Survival-Prediction-Model-Comparison
This project compares multiple machine learning algorithms to predict passenger survival using the Titanic dataset. The goal is to evaluate how different models perform on the same classification problem.
