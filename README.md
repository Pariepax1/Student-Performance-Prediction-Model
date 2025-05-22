# Student Performance Prediction Model

This project explores how various student behaviors—such as study time, sleep, and extracurricular activities—impact academic performance. The goal is to develop a predictive model to support data-driven decision-making in education. Linear regression was selected as the primary method due to its ability to model continuous outcomes like performance scores. The dataset, sourced from [Kaggle](https://www.kaggle.com/datasets/nikhil7280/student-performance-multiple-linear-regression), contains 10,000 records across multiple features.

---

## 🧰 Tools & Technologies

- **Languages:** Python  
- **Libraries:** Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn  
- **Techniques:** Linear Regression, Decision Tree Regression, Data Cleaning, Feature Engineering, Model Evaluation  

---

## 🧹 Data Preprocessing

- Verified there were **no missing values**  
- Converted categorical features using one-hot encoding  
- Final dataset included features like:  
  - `Hours Studied`, `Previous Scores`, `Sleep Hours`, `Extracurricular Activities`, `Sample Question Papers Practiced`

---

## 🧪 Experiments

### ✅ Experiment 1: Linear Regression (All Features)
- **MSE:** 4.08  
- **MAE:** 1.61  
- **R²:** 0.99  
- 📊 Visualization of predicted vs. actual performance showed strong accuracy

### ✅ Experiment 2: Linear Regression (Removed 1 Feature)
- Dropped `Sample Question Papers Practiced`  
- **MSE:** 4.42  
- **MAE:** 1.68  
- **R²:** 0.99  
- Slight performance decline → showed importance of even small features

### ✅ Experiment 3: Decision Tree Regressor
- **MSE:** 8.81  
- **MAE:** 2.34  
- **R²:** 0.98  
- Performance worsened, showing that **linear regression outperformed** a non-linear model on this dataset

---

## 📈 Key Visuals

- Bar charts comparing **actual vs predicted performance** for the first 20 students in each experiment  
- Confirmed linear regression consistently delivered better predictions

---

## 🌍 Impact

This model can help educators identify students who may need academic support early on. It allows schools to better understand which factors influence performance. However, ethical concerns include potential bias in predictions and the risk of unfair labeling. It's important these models are used to guide and support—not restrict—student success.

---

## 🧠 Conclusion

This project taught me how model choice and feature selection directly affect predictive accuracy. Linear regression provided strong, consistent results. Removing even one feature reduced performance slightly, and switching to a decision tree confirmed that linear methods were better suited for this dataset.

---

## 🔗 Dataset Source

[Kaggle: Student Performance Dataset](https://www.kaggle.com/datasets/nikhil7280/student-performance-multiple-linear-regression)

