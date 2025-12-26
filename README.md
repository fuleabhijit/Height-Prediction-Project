# 📏 End-to-End Height Prediction using Machine Learning

This is my **first machine learning project**, built to understand the complete workflow of a regression problem.  
The project predicts a person’s height based on their weight using **Linear Regression** and core ML concepts implemented in Python.

---

## 🎯 Project Objective

To build a simple yet complete machine learning model that:
- Learns the relationship between weight and height  
- Applies proper preprocessing and evaluation techniques  
- Demonstrates an end-to-end ML pipeline suitable for beginners  

---

## ⚙️ Project Workflow

### 1️⃣ Data Loading
- Dataset: `height-weight.csv`
- Features:
  - **Weight** (input)
  - **Height** (target)

---

### 2️⃣ Data Visualization
- Visualized the relationship between height and weight using scatter plots  
- Observed a clear **linear correlation**, making it suitable for Linear Regression  

---

### 3️⃣ Data Preprocessing
- Scaled numerical features using **StandardScaler**
- Ensured balanced model training and stable performance  

---

### 4️⃣ Model Building
- Implemented **Linear Regression** using `scikit-learn`
- Trained the model to learn the best-fitting line between weight and height  

---

### 5️⃣ Model Evaluation
The model was evaluated using the following metrics:
- R² Score
- Mean Squared Error (MSE)
- Root Mean Squared Error (RMSE)
- Mean Absolute Error (MAE)

---

## 📊 Results

| Metric | Value |
|------|------|
| Model | Linear Regression |
| R² Score | 0.77 |
| Regression Equation | Height = 157.5 + 17.03 × Weight |
| Example Prediction | 80 kg → ≈ 163.01 cm |

🔹 The model explains **~77% of the variance** in height using weight, which is a strong result for a single-feature regression model.

---

## 🧰 Tech Stack & Requirements

- **Python**
- **Libraries Used**
  - pandas
  - scikit-learn
  - matplotlib
  - seaborn

### Install dependencies
```bash
pip install pandas scikit-learn matplotlib seaborn
