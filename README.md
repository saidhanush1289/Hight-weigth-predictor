# Height & Weight Predictor

A machine learning project that predicts an individual's weight based on their height (and/or gender) using regression analysis.

## 📋 Overview
This project explores the correlation between human height and weight by training a supervised machine learning model on anthropometric data. It includes data preprocessing, exploratory data analysis (EDA), model training, evaluation, and prediction functionality.

## 🚀 Features
- **Data Preprocessing:** Handles missing values, outliers, and feature encoding (if gender is included).
- **Exploratory Data Analysis:** Visualizes height-weight distributions and linear relationships.
- **Model Training & Evaluation:** Trains regression models (e.g., Linear Regression) and evaluates performance using metrics such as $R^2$ Score, Mean Absolute Error (MAE), and Mean Squared Error (MSE).
- **Interactive Predictions:** Allows users to input a height value to get an instant weight prediction.

## 🛠️ Tech Stack
- **Language:** Python 3.x
- **Libraries:** Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn
- **Web Framework (Optional):** Flask / Streamlit *(remove if using only Jupyter Notebook)*

## 📂 Project Structure
```text
Hight-weigth-predictor/
│
├── dataset/                # Dataset file (e.g., weight-height.csv)
├── notebooks/              # Jupyter Notebooks for EDA and model training
├── app.py                  # Web app script (if applicable)
├── model.pkl               # Saved trained model (if applicable)
├── requirements.txt        # Python dependencies
└── README.md               # Project documentation

git clone [https://github.com/saidhanush1289/Hight-weigth-predictor.git](https://github.com/saidhanush1289/Hight-weigth-predictor.git)
cd Hight-weigth-predictor
