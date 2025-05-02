# NeuroNexus Titanic Survival Prediction 🚢

This project uses the classic **Titanic dataset** from Kaggle to predict whether a passenger survived the Titanic disaster, based on features like age, gender, ticket class, fare, and cabin.

---

## About the Project

The main goal was to experiment with different machine learning models and compare their performance. It’s a beginner-friendly project to practice data cleaning, feature engineering, and model evaluation.

---

## Dataset

* Source: [Kaggle Titanic Dataset](https://www.kaggle.com/c/titanic)
* Features used:

  * Age
  * Gender
  * Ticket Class (Pclass)
  * Fare
  * Cabin
  * Embarked
  * Survival (Target variable)

---

## Models and Results 📊

| Model                  | Test Accuracy |
| ---------------------- | ------------- |
| Random Forest          | **80.44%**    |
| Gradient Boosting      | 79.32%        |
| Logistic Regression    | 78.21%        |
| Support Vector Machine | 63.68%        |

🔍 **Observations:**

* Random Forest performed the best overall.
* Gradient Boosting wasn't far behind.
* Logistic Regression gave a decent baseline but showed a convergence warning (probably got tired of iterating 😅).
* SVM struggled on this dataset without heavy tuning

---

## How to Run

1. Download the dataset from Kaggle and place it in your working directory.
2. Open the Jupyter notebook.
3. Run the cells and follow along with data exploration, model training, and evaluation!
---

## Future Plans

* Tune hyperparameters for even better model accuracy.
* Try advanced algorithms like XGBoost or LightGBM.
* Deploy the model with a simple Streamlit app for live survival predictions.

---

> This was a quick and fun project —
> 
\#DataScience #MachineLearning #TitanicPrediction #Python #BeginnerProject #LearningJourney

---
