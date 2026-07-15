# 🚗 Car Price Prediction with Machine Learning

## 📌 Project Overview

This project is part of the **Oasis Infobyte Data Science Internship (OIBSIP)**.

The objective of this project is to develop a Machine Learning model that predicts the selling price of used cars based on various vehicle attributes. The project follows a complete data science workflow, including data preprocessing, exploratory data analysis (EDA), feature engineering, model training, evaluation, and comparison.

---

## 🎯 Objective

- Load and explore the car price dataset.
- Perform data cleaning and preprocessing.
- Engineer useful features for better prediction.
- Visualize relationships between different variables.
- Train multiple regression models.
- Compare model performance and identify the best-performing model.

---

## 🛠️ Tech Stack

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook / Google Colab

---

## 📂 Dataset

The project uses a **Car Price Prediction Dataset** containing information about used vehicles.

The dataset includes features such as:

- Car Name
- Year
- Selling Price
- Present Price
- Kilometers Driven
- Fuel Type
- Seller Type
- Transmission
- Owner
- Other vehicle-related attributes

---

## 📊 Project Workflow

### 1. Data Loading
- Imported the dataset using Pandas.
- Inspected the dataset structure.

### 2. Exploratory Data Analysis (EDA)
Performed:

- Dataset shape
- Dataset information
- Data types
- Missing value analysis
- Duplicate value analysis
- Statistical summary
- Unique categorical values

### 3. Data Cleaning

- Removed duplicate records
- Handled missing values
- Corrected inconsistent categorical values
- Removed unnecessary columns where required

### 4. Feature Engineering

- Created a **Car_Age** feature from the manufacturing year.
- Extracted the car brand from the vehicle name.
- Prepared the dataset for machine learning.

### 5. Data Visualization

Created various visualizations including:

- Selling Price Distribution
- Box Plots
- Scatter Plots
- Count Plots
- Correlation Heatmap
- Pair Plot

### 6. Feature Encoding

- Applied One-Hot Encoding for categorical variables.

### 7. Model Building

The following regression models were trained:

- Linear Regression
- Random Forest Regressor

### 8. Model Evaluation

Both models were evaluated using:

- Mean Absolute Error (MAE)
- Root Mean Squared Error (RMSE)
- R² Score

### 9. Model Comparison

Compared both models to determine the most accurate prediction model.

### 10. Feature Importance

Visualized feature importance using the Random Forest model.

---

## 📈 Visualizations Included

- Selling Price Histogram
- Box Plots
- Scatter Plots
- Count Plots
- Correlation Heatmap
- Pair Plot
- Feature Importance Chart
- Actual vs Predicted Values Comparison

---

## 🤖 Machine Learning Models

- Linear Regression
- Random Forest Regressor

---

## 📊 Evaluation Metrics

The models were evaluated using:

- Mean Absolute Error (MAE)
- Root Mean Squared Error (RMSE)
- R² Score

---

## 🏆 Results

The performance of both regression models was compared using standard evaluation metrics.

The **Random Forest Regressor** achieved better predictive performance than the baseline Linear Regression model, demonstrating its ability to capture complex relationships within the dataset.

---

## 📁 Project Structure

```
DataScience-Task3-CarPricePrediction/
│
├── Car_Price_Prediction.ipynb
├── README.md
├── CAR DETAILS FROM CAR DEKHO.csv
└── images/ (Optional)
```

---

## ▶️ How to Run

### 1. Clone the repository

```bash
git clone https://github.com/yourusername/OIBSIP.git
```

### 2. Install dependencies

```bash
pip install pandas numpy matplotlib seaborn scikit-learn
```

### 3. Open the notebook

```bash
jupyter notebook Car_Price_Prediction.ipynb
```

or upload the notebook to **Google Colab** and run all cells.

---

## 📚 Libraries Used

- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

---

## 🎓 Learning Outcomes

Through this project, I learned:

- Data preprocessing and cleaning
- Exploratory Data Analysis (EDA)
- Feature Engineering
- Data Visualization
- One-Hot Encoding
- Regression Algorithms
- Model Evaluation
- Feature Importance Analysis
- Predictive Modeling

---

## 📌 Internship Information

**Internship:** Oasis Infobyte Data Science Internship (OIBSIP)

**Task:** Task 3 – Car Price Prediction with Machine Learning

---

## 👨‍💻 Author

**Pratyush Kumar**

B.Tech Computer Science Engineering

Data Science Intern – Oasis Infobyte

---

## 🙏 Acknowledgements

- Oasis Infobyte
- Scikit-learn
- Pandas
- Matplotlib
- Seaborn
- Python Community