# 🚢 Titanic Survival Prediction

This project aims to predict the survival of passengers aboard the Titanic using machine learning models. The dataset contains information about passengers such as age, gender, ticket class, and other relevant features.

---

## 🎯 Objectives
- Clean and preprocess the Titanic dataset.
- Handle missing values, encode categorical variables, and normalize numerical data.
- Train and evaluate classification models to predict passenger survival.
- Choose the best-performing model and save it for future use.

---

## 🗂️ Directory Structure
/Titanic-Survival-Prediction
├── /data
│   ├── train.csv
│   ├── test.csv
├── /models
│   └── best_model.pkl
├── /notebooks
│   └── code.ipynb
├── /src
│   ├── preprocess.py
│   └── train_model.py
├── requirements.txt
└── README.md

## 📚 Dataset Information
The dataset includes the following columns:

- `PassengerId`: Unique ID for each passenger.
- `Name`: Name of the passenger.
- `Age`: Age of the passenger.
- `Sex`: Gender (male/female).
- `SibSp`: Number of siblings/spouses aboard.
- `Parch`: Number of parents/children aboard.
- `Ticket`: Ticket number.
- `Fare`: Passenger fare.
- `Cabin`: Cabin number (if assigned).
- `Embarked`: Port of embarkation (C = Cherbourg, Q = Queenstown, S = Southampton).
- `Survived`: Survival status (0 = No, 1 = Yes).

🛠️ 6. How to Run the Project

## How to Run the Project
1. **Clone the Repository:**
```bash
git clone https://github.com/RevanthReddy2111/titanic_survival_prediction.git
cd titanic-survival-prediction


2. **Run the Notebook:**

Open the Jupyter Notebook:

Open code.ipynb and execute the cells step by step.


📊 Model Evaluation
The performance of the models was evaluated based on:

Accuracy: Percentage of correctly predicted instances.

Precision: Proportion of positive predictions that are correct.

Recall: Ability to detect positive instances.

F1-Score: Harmonic mean of precision and recall.

After evaluating different models:

Random Forest Classifier were considered.
🔍 Results and Future Scope
The Random Forest model provided the best performance with an accuracy of around 85%.

Future improvements can include:

Hyperparameter tuning to further improve accuracy.

Experimenting with ensemble models.

Adding feature engineering to extract more meaningful insights.

🤝 Contribution
Feel free to contribute to the project. To contribute:

Fork the repository.

Create a new branch.

Make your changes and commit them.

Submit a pull request.

📜 Acknowledgments
Dataset from Kaggle Titanic Dataset

Open-source libraries including Pandas, NumPy, Matplotlib, and Scikit-Learn.

yaml
Copy
Edit

---

## ✅ **Final Checklist:**
1. Create a `/models` folder and move `best_model.pkl` there.
2. Create `requirements.txt` with the required libraries.
3. Add `README.md` in the root folder.

You're good to go! 🚀 Let me know if you encounter any issues! 😊
