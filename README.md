# 💻 Laptop Price Prediction Using Machine Learning

## 📌 Project Overview

Laptop Price Prediction is a Machine Learning project that analyzes laptop specifications and predicts their market prices based on hardware features. The project combines **Exploratory Data Analysis (EDA)**, **Data Preprocessing**, **Feature Engineering**, and **Regression Models** to identify the factors that have the greatest impact on laptop pricing.

The objective is to build an accurate regression model capable of estimating laptop prices while providing insights into the relationship between hardware specifications and market value.

---

# 🎯 Problem Statement

Laptop prices vary significantly depending on hardware specifications such as processor, RAM, storage, graphics card, operating system, and brand. Determining a fair market price based on these features can be challenging for both customers and sellers.

This project aims to analyze these factors and develop a Machine Learning model capable of accurately predicting laptop prices.

---

# 🚀 Key Features

### 📊 Exploratory Data Analysis (EDA)

Performed comprehensive data analysis to:

- Understand feature distributions
- Analyze feature correlations
- Detect missing values and outliers
- Identify the most influential factors affecting laptop prices
- Visualize trends using different statistical plots

---

### ⚙️ Data Preprocessing

Built a complete preprocessing pipeline including:

- Data Cleaning
- Missing Value Handling
- Feature Engineering
- Encoding Categorical Variables
- Feature Scaling
- Train/Test Split

---

### 🤖 Machine Learning Models

Implemented and compared multiple regression algorithms:

- Linear Regression
- Support Vector Regression (SVR)
- Random Forest Regressor

Applied **GridSearchCV** for hyperparameter tuning to optimize model performance.

---

### 📈 Model Evaluation

Models were evaluated using:

- R² Score
- Root Mean Squared Error (RMSE)
- Cross Validation

The best-performing model was selected based on predictive accuracy and generalization performance.

---

# 🛠 Technologies Used

## Programming Language

- Python

## Data Analysis

- Pandas
- NumPy

## Data Visualization

- Matplotlib

## Machine Learning

- Scikit-learn
- GridSearchCV

## Development Environment

- Jupyter Notebook

---

# 🔄 Project Workflow

1. Load Dataset
2. Data Cleaning
3. Exploratory Data Analysis (EDA)
4. Feature Engineering
5. Data Preprocessing
6. Train Regression Models
7. Hyperparameter Tuning
8. Model Evaluation
9. Price Prediction

---

# 📊 Models Comparison

| Model | Purpose |
|--------|---------|
| **Linear Regression** | Baseline regression model |
| **Support Vector Regression (SVR)** | Capture nonlinear relationships |
| **Random Forest Regressor** | Ensemble learning for higher prediction accuracy |

---

# 📈 Project Outcomes

- Identified the most influential hardware features affecting laptop prices.
- Built and compared multiple regression models.
- Optimized model performance using GridSearchCV.
- Developed an end-to-end machine learning workflow for price prediction.

---

# ⚙️ Installation

## Clone the Repository

```bash
git clone https://github.com/yourusername/Laptop-Price-Prediction.git
cd Laptop-Price-Prediction
```

## Install Dependencies

```bash
pip install -r requirements.txt
```

## Run the Notebook

```bash
jupyter notebook
```

Open the notebook and execute the cells sequentially.

---

# 📂 Project Structure

```
├── data/
│   └── laptop_data.csv
│
├── notebooks/
│   └── Laptop_Price_Prediction.ipynb
│
├── images/
│
├── requirements.txt
└── README.md
```

---

# 🎓 Learning Outcomes

Through this project, I gained practical experience in:

- Exploratory Data Analysis (EDA)
- Data Cleaning and Preprocessing
- Feature Engineering
- Regression Algorithms
- Hyperparameter Tuning
- Model Evaluation
- Data Visualization
- Machine Learning Workflow

---

# 👨‍💻 My Contribution

I independently developed the complete project, including:

- Collecting and exploring the dataset.
- Performing exploratory data analysis (EDA).
- Cleaning and preprocessing the data.
- Engineering relevant features for model training.
- Developing and comparing multiple regression models.
- Optimizing model performance using GridSearchCV.
- Evaluating model performance and selecting the best-performing model.

---

# 🚀 Future Improvements

- Deploy the model as a web application using Flask or FastAPI.
- Integrate XGBoost and LightGBM for performance comparison.
- Build an interactive price prediction dashboard.
- Automate the complete preprocessing and prediction pipeline.
