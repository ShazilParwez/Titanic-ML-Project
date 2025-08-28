# 🚢 Titanic Survival Prediction (Mini ML Project)

## 📌 Problem Statement  
The goal of this project is to **predict whether a passenger survived** the Titanic disaster, based on features like:  
- Passenger class (Pclass)  
- Gender (Sex)  
- Age  
- Fare  
- Embarkation point (Embarked)  

---

## 📊 Dataset  
- Source: [Kaggle Titanic Dataset](https://www.kaggle.com/c/titanic/data)  
- Rows: 891 passengers  
- Target variable: **Survived** (0 = Died, 1 = Survived)  

---

## 🔎 Workflow  
1. **Data Loading** – Loaded Titanic dataset.  
2. **EDA** – Visualized survival distribution, survival by gender & passenger class.  
3. **Preprocessing** –  
   - Filled missing values (Age → median, Embarked → mode).  
   - Encoded categorical variables (Sex, Embarked).  
   - Scaled numerical features (Age, Fare).  
4. **Model Training** – Logistic Regression.  
5. **Evaluation** – Accuracy, classification report, and confusion matrix.  

---

## 📈 Results  
- **Accuracy:** ~78% (varies slightly per run)  
- **Insights:**  
  - Women had a higher chance of survival.  
  - 1st class passengers were more likely to survive than 3rd class.  

---

## 🛠 Tech Stack  
- Python  
- Pandas, NumPy  
- Matplotlib, Seaborn (for EDA & visualization)  
- Scikit-learn (for ML model)  

---
