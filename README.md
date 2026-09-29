# House Price Prediction using Regression Techniques

A machine learning project that predicts house prices using regression algorithms. The project demonstrates a complete machine learning workflow, from data preprocessing and exploratory data analysis to model training, evaluation, comparison, and prediction.

## 📌 Project Overview

The objective of this project is to predict the **Sale Price** of houses based on various property features such as overall quality, living area, garage capacity, and other numerical and categorical attributes.

The project uses multiple regression techniques and compares their performance using standard evaluation metrics.

## 🤖 Machine Learning Models

The following models are implemented:

- **Linear Regression**
- **Ridge Regression**
- **Random Forest Regressor**

## 📊 Evaluation Metrics

The models are evaluated using:

- **MAE (Mean Absolute Error)** – Measures the average absolute difference between actual and predicted prices.
- **RMSE (Root Mean Squared Error)** – Measures prediction error while giving greater weight to larger errors.
- **R² Score** – Measures how well the model explains the variation in house prices.

## 🔄 Project Workflow

```text
Dataset
   ↓
Data Exploration
   ↓
Data Preprocessing
   ↓
Handle Missing Values
   ↓
Encode Categorical Features
   ↓
Train-Test Split
   ↓
Model Training
   ↓
Model Evaluation
   ↓
Model Comparison
   ↓
House Price Prediction
```

## 🛠️ Technologies Used

- Python
- NumPy
- Pandas
- Matplotlib
- Scikit-learn
- Jupyter Notebook

## 📂 Dataset

The project uses the **House Prices: Advanced Regression Techniques** dataset from Kaggle.

Target variable:

```text
SalePrice
```

The `Id` column is excluded from model training because it is only an identifier.

## ⚙️ Installation

Install the required Python packages using:

```bash
pip install numpy pandas matplotlib scikit-learn jupyter
```

## ▶️ How to Run

1. Download or clone this repository.
2. Place the Kaggle `train.csv` dataset in the same folder as the notebook.
3. Open `Predicting_House_Prices_Regression.ipynb` using Jupyter Notebook or VS Code.
4. Run the cells from top to bottom.

## 📁 Project Structure

```text
house-price-prediction-regression/
│
├── Predicting_House_Prices_Regression.ipynb
├── train.csv
└── README.md
```

## 📈 Results

The notebook trains and evaluates all three models and presents their performance using **MAE, RMSE, and R² Score**. It also includes an **Actual vs Predicted Prices** visualization and a sample house-price prediction.

The exact results may vary slightly depending on the dataset version and execution environment.

## 🎯 Learning Outcomes

Through this project, I learned how to:

- Perform Exploratory Data Analysis (EDA)
- Handle missing values
- Process numerical and categorical data
- Build machine learning pipelines
- Train regression models
- Evaluate and compare model performance
- Make predictions on new data

## 👨‍💻 Author

**Anirban Dey Sarkar**

Computer Science & Engineering Student

---

⭐ If you found this project useful, feel free to star the repository!
