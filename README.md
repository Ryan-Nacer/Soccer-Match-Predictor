# ⚽ Football Match Outcome Predictor  
### Machine Learning Project (2020–2022 Data)

![Python](https://img.shields.io/badge/Python-3.x-blue)
![Pandas](https://img.shields.io/badge/Pandas-Data%20Processing-orange)
![Scikit-Learn](https://img.shields.io/badge/Model-RandomForest-green)

---

## 📌 Overview

Built a machine learning pipeline to predict whether a football team will **win a match**, using historical match data and engineered performance features.

The project focuses on improving prediction quality through contextual and rolling statistics.

---

## 🧠 Feature Engineering

- Home/Away encoding  
- Opponent encoding  
- Kickoff hour extraction  
- Day-of-week feature  
- **Rolling 3-match performance averages** (team form)

Rolling features capture short-term momentum while preventing data leakage.

---

## 🌳 Model

- **RandomForestClassifier**
- 100 trees  
- `min_samples_split=10`
- Chronological train/test split (before vs after 2022)

---

## 📊 Results

| Model Version | Precision | Accuracy |
|--------------|----------|----------|
| Context Only | 0.xx | 0.xx |
| + Rolling Features | 0.xx | 0.xx |

Rolling performance features improved predictive performance by incorporating recent team form.

---

## 🔎 Skills Demonstrated

- Data preprocessing with Pandas  
- Categorical encoding  
- Time-aware train/test splitting  
- Rolling window statistics  
- Ensemble modeling (Random Forest)  
- Model evaluation (Precision, Accuracy)

---

## 📂 Tech Stack

- Python  
- Pandas  
- Scikit-Learn  
