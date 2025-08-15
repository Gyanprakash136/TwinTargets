🏢 Energy Efficiency Prediction using Multi-Output Linear Regression

This project predicts heating load (Y1) and cooling load (Y2) of buildings using their architectural design parameters. The model is built using Scikit-learn's LinearRegression with support for multi-output regression.

📌 Project Overview

Dataset: UCI Energy Efficiency Dataset

Goal: Predict Heating Load (Y1) and Cooling Load (Y2) from 8 building design parameters.

Approach:

Multi-output Linear Regression

Train/test split

Feature scaling

Model evaluation with R²

Visualization of Predicted vs Actual for both training and test sets

📊 Dataset Description
Variable	Description	Type	Units
X1	Relative Compactness	Continuous	-
X2	Surface Area	Continuous	m²
X3	Wall Area	Continuous	m²
X4	Roof Area	Continuous	m²
X5	Overall Height	Continuous	m
X6	Orientation	Integer (2–5)	-
X7	Glazing Area	Continuous	%
X8	Glazing Area Distribution	Integer (1–5)	-
Y1	Heating Load	Continuous	kWh/m²
Y2	Cooling Load	Continuous	kWh/m²
⚙️ Tech Stack

Python 3.x

Libraries:

pandas – Data manipulation

numpy – Numerical operations

matplotlib & seaborn – Visualization

scikit-learn – Machine Learning models & metrics

🚀 Results

Training Set Performance

Y1 (Heating Load): R² = 0.924

Y2 (Cooling Load): R² = 0.886

Test Set Performance

Y1 (Heating Load): R² = 0.922

Y2 (Cooling Load): R² = 0.896

📈 Visualizations
Training Set – Predicted vs Actual
<img width="1133" height="490" alt="image" src="https://github.com/user-attachments/assets/e34c67f3-c7b5-42ba-a0b1-ec6ded1f369b" />


Test Set – Predicted vs Actual
<img width="1129" height="484" alt="image" src="https://github.com/user-attachments/assets/31b789b6-bf10-4d48-81d2-03efc9d2f54b" />


📄 How to Run
# Clone the repository
git clone https://github.com/<your-username>/<repo-name>.git

# Navigate to project directory
cd <repo-name>

# Install dependencies
pip install -r requirements.txt

# Run the script
python energy_efficiency_regression.py

💡 Key Learnings

How to use MultiOutputRegressor in Scikit-learn


- Feature scaling impact on linear regression

- Visualizing regression results with scatter plots and R² values

- Handling and interpreting multiple regression targets# TwinTargets
