# 🏠 House Price Prediction

A machine learning project that predicts house prices based on various property features. This project demonstrates the complete machine learning workflow, including data preprocessing, exploratory data analysis, feature engineering, model training, hyperparameter tuning, and prediction generation.

---

## 📌 Project Overview

The objective of this project is to build a regression model capable of accurately predicting house prices using historical housing data. Multiple machine learning algorithms were explored, and the best-performing model was selected based on evaluation metrics.

---

## 📂 Dataset

The project uses the **House Prices: Advanced Regression Techniques** dataset, which contains information about residential homes and their corresponding sale prices.

### Files
- `train.csv` – Training dataset
- `test.csv` – Test dataset
- `sample_submission.csv` – Sample submission format
- `data_description.txt` – Description of all dataset features

---

## 🛠️ Technologies Used

- Python
- NumPy
- Pandas
- Matplotlib
- Seaborn
- Scikit-learn
- CatBoost
- Jupyter Notebook

---

## 🔄 Workflow

1. Data Loading
2. Data Cleaning
3. Exploratory Data Analysis (EDA)
4. Feature Engineering
5. Data Preprocessing
6. Model Training
7. Hyperparameter Tuning
8. Model Evaluation
9. Prediction Generation

---

## 📊 Models Explored

- Linear Regression
- Random Forest Regressor
- Gradient Boosting Regressor
- CatBoost Regressor

---

## 📈 Evaluation Metrics

The models were evaluated using:

- Mean Absolute Error (MAE)
- Mean Squared Error (MSE)
- Root Mean Squared Error (RMSE)
- R² Score

---

## 📁 Project Structure

```
House Price Prediction Project/
│
├── data/
│   └── raw/
│       ├── train.csv
│       ├── test.csv
│       ├── sample_submission.csv
│       └── data_description.txt
│
├── notebooks/
│   └── HousePricePrediction.ipynb
│
├── requirements.txt
├── submission.csv
└── README.md
```

---

## 🚀 How to Run

### Clone the repository

```bash
git clone <repository-url>
```

### Navigate to the project

```bash
cd "House Price Prediction Project"
```

### Install dependencies

```bash
pip install -r requirements.txt
```

### Launch Jupyter Notebook

```bash
jupyter notebook
```

Open `HousePricePrediction.ipynb` and run all the cells.

---

## 🎯 Results

The trained model predicts house prices for unseen properties and generates a `submission.csv` file containing the predicted values.

---

## 📚 Learning Outcomes

Through this project, I gained practical experience in:

- Data preprocessing
- Exploratory Data Analysis
- Feature Engineering
- Regression Modeling
- Hyperparameter Tuning
- Model Evaluation
- End-to-End Machine Learning Workflow

---

## 📜 License

This project is created for learning and educational purposes.
