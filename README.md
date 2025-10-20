# 🚢 Titanic Survival Prediction (Kaggle Competition)

A complete beginner-friendly machine learning project predicting passenger survival on the Titanic dataset.  
Built using Python, Pandas, and Scikit-learn. Submitted to the official Kaggle competition.

---

## 🎯 Objective
To predict which passengers survived the Titanic disaster based on attributes such as age, sex, class, and family size.

---

## 🧠 Key Concepts
- Handling missing data
- Feature engineering
- Categorical encoding
- Model evaluation (cross-validation)
- Kaggle submission workflow

---

## 🧩 Project Workflow

1. **Exploratory Data Analysis (EDA)**  
   - Checked missing values and class distribution.  
   - Visualized key relationships between features and survival rate.

2. **Data Cleaning**  
   - Filled missing `Age` and `Embarked` values.  
   - Dropped highly-missing `Cabin` column.

3. **Feature Engineering**  
   - Created `IsAlone`, `FamilySize`, `FarePerPerson`.  
   - Extracted titles (Mr, Mrs, Miss, etc.) from passenger names.

4. **Modeling**  
   - Logistic Regression and Random Forest Classifiers.  
   - Cross-validation accuracy ≈ **0.84**  
   - Kaggle submission score: **0.76555**

5. **Submission**  
   - Generated and uploaded `submission_v1.csv` to Kaggle.

---

## ⚙️ Tools Used
- Python (Pandas, NumPy, Scikit-learn)
- Kaggle Notebooks
- Matplotlib, Seaborn
- GitHub for version control

---

## 📈 Results
| Metric | Value |
|--------|--------|
| Cross-validation Accuracy | 0.8395 |
| Kaggle Public Score | **0.76555** |
| Top Features | Sex, Pclass, FamilySize, Title |

---

## 🔮 Next Steps
- Try feature scaling and hyperparameter tuning.  
- Add ensemble models (XGBoost, CatBoost).  
- Extend the pipeline for real-world datasets (HR analytics, health, finance).

---

## 📂 File Structure
```
titanic-survival-analysis/
├── titanic_v1_baseline_logreg_RF.ipynb   # Main notebook
├── submission_v1.csv                     # Kaggle submission file
└── README.md                             # Project documentation
```

---

## 🧑‍💻 Author
**Treasure Iwuagwu**  
Data Analyst | MBA (Finance) | AR/VR Enthusiast  
[LinkedIn Profile](https://www.linkedin.com/in/treasure-nweze-2266b3154)
