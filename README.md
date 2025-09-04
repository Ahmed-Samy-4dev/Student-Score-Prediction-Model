# 📊 Student Score Prediction Model

This project predicts the exam score of students based on their study hours, sleep,etc..
It applies **Machine Learning models** such as **Linear Regression** and **Polynomial Regression**.

---

## 🚀 Project Workflow
1. **Data Exploration & Cleaning**  
   - Checked data types, missing values, and unique values.
  
2. **Feature Preparation**
   - Encoded categorical features to increase r2_score.

3. **Model Training**  
   - **Linear Regression**: Represented the data more properly due to the linear relationship of features. 
   - **Polynomial Regression**: Slightly increased MAE & MSE with the same R2-score.

4. **Evaluation Metrics**  
   - MAE, MSE, and R2-Score.  
   - Compared models R2-Score through a bar plot.  

---

## 📈 Results
| Model                 | MAE    | MSE    | R2-score | 
|-----------------------|--------|--------|----------| 
| Linear Regression     | ~8e-14 | ~1e-26 | ~1       | 
| Polynomial Regression | ~3e-09 | ~1e-17 | ~1       | 

- Linear Regression performed slightly better due to the linear relationship of features. 

**Final Choice:** Linear Regression performed best for this dataset.

---

## 📦 Dataset
- Student Performance Factors (Kaggle)

---

## 🛠️ Tech Stack
- Python 🐍  
- Pandas, NumPy  
- Matplotlib
- Seaborn
- scikit-learn  

---

## 📂 Project Structure
student-score-prediction-model/

│── data/

│     └── StudentPerformanceFactors.csv       # Original dataset

│

│── notebooks/

│     └── score_prediction.ipynb  # Jupyter Notebook with full workflow

│

│── README.md                           # Project documentation

│── requirements.txt                    # Python dependencies

│── .gitignore                          # Ignore unnecessary files

│── LICENSE                             # License file
