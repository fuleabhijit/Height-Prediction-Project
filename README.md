🌟 End-to-End Height Prediction Project
📘 Overview

This project walks through the complete process of building a machine learning regression model that predicts a person’s height based on their weight. It’s a perfect beginner-friendly example of applying core ML concepts — from data preprocessing to evaluation — using Python.

⚙️ Project Workflow

Data Loading

Dataset: height-weight.csv

Columns: Weight, Height

Data Visualization

Explored the relationship between height and weight using scatter plots.

Observed a clear linear correlation.

Preprocessing

Scaled numerical features using StandardScaler for balanced model performance.

Model Building

Implemented Linear Regression using scikit-learn.

Trained the model to learn the best-fitting line between weight and height.

Evaluation

Metrics used: R², RMSE, MSE, MAE

These metrics helped assess accuracy and error magnitude.

📊 Results
Metric	Value
Model	Linear Regression
R² Score	0.77
Equation	Height = 157.5 + 17.03 × Weight
Example Prediction	80 kg → ≈ 163.01 cm

The model explains roughly 77% of the variability in height based on weight — a strong start for a simple one-feature regression!

🧰 Requirements

Make sure you have the following dependencies installed:

pip install pandas scikit-learn matplotlib seaborn

🚀 How to Run

Clone this repository:

git clone https://github.com/your-username/height-prediction.git
cd height-prediction


Place the height-weight.csv dataset in your working directory.

Run the notebook or Python script to reproduce results:

jupyter notebook Height_Prediction.ipynb


or

python height_prediction.py
