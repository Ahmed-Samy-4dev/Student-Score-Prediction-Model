# 📊 Student Score Prediction Model

This project predicts the exam score of students based on their study hours, sleep,etc..
It applies **Machine Learning models** such as **Linear Regression** and **Polynomial Regression**.

---

## 🚀 Project Workflow
1. **Data Exploration & Cleaning**  
   - Checked data types, missing values, and unique values.

2. **Model Training**  
   - **Linear Regression**: Represented the data more properly with a slight increase in r2-score.  
   - **Polynomial Regression**: Slightly increased MAE & MSE but decreased the r2-score.

3. **Evaluation Metrics**  
   - MAE, MSE, and R2-Score.  
   - Compared models R2-Score through a bar plot.  

---

## 📈 Results
| Model                 | MAE   | MSE   | R2-score | 
|-----------------------|-------|-------|----------| 
| Linear Regression     | ~1.25 | ~4.45 | ~0.67    | 
| Polynomial Regression | ~1.26 | ~4.49 | ~0.66    | 

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
