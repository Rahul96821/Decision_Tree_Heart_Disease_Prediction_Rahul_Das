# 🫀 Heart Disease Prediction using Decision Tree

## 📌 Project Overview
This project applies **Decision Tree Classification** to predict the presence of **heart disease** based on patient health attributes.  
The goal is to build a simple, interpretable machine learning model that can provide insights into risk factors such as **age, sex, blood pressure, and cholesterol**.

---

## 📊 Dataset
- Total samples: **270**
- Features: **4**
  - `age` – Age of the patient
  - `sex` – Gender (0 = Female, 1 = Male)
  - `BP` – Resting blood pressure
  - `cholestrol` – Serum cholesterol level
- Target:
  - `heart disease` – 1 = Disease, 0 = No Disease

---

## ⚙️ Workflow
1. **Data Preprocessing**  
   - Split into training (70%) and testing (30%) sets.
2. **Model Training**  
   - Decision Tree Classifier with `max_depth = 3`.
3. **Evaluation**  
   - Accuracy, confusion matrix, and interpretability through visualization.

---

## 📈 Results
- **Training Accuracy**: ~74%  
- **Test Accuracy**: ~60%  
- The model correctly identifies **No Disease** cases more reliably than **Disease** cases.  
- **Limitations**: Higher number of false negatives → risky for medical applications.  

---

## 🔍 Visualization
The decision tree was visualized using **Graphviz** and shows how features like age, sex, BP, and cholesterol influence predictions.  

Example rules:
- Younger + Female + Low Cholesterol → Mostly **No Disease**  
- Older + Male + High Cholesterol → Mostly **Disease**

---

## 🛠️ Tech Stack
- Python 🐍
- pandas, numpy
- scikit-learn
- matplotlib, graphviz / pydotplus



# Run Jupyter Notebook
jupyter notebook
