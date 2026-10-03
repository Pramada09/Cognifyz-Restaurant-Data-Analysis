# Cognifyz Restaurant Data Analysis

## 📌 Project Overview

This project was completed as part of the Cognifyz Data Analysis Internship.

The project focuses on analyzing restaurant data using Python, Pandas, NumPy, Scikit-learn, and Matplotlib. The analysis covers data exploration, data preprocessing, predictive modeling, customer preference analysis, and data visualization.

---

## 📊 Dataset

The dataset contains **9,551 restaurant records** and **21 features**.

Important features include:

- Restaurant Name
- City
- Country Code
- Cuisines
- Average Cost for two
- Price range
- Table Booking
- Online Delivery
- Aggregate Rating
- Rating Text
- Votes

---

# 🚀 Levels Completed

## Level 1

The Level 1 tasks focused on understanding and analyzing the restaurant dataset through data exploration and preprocessing.

Key activities included:

- Dataset exploration
- Missing value analysis
- Rating analysis
- Restaurant-related feature analysis
- Data preprocessing

---

# Level 2

Level 2 focused on deeper restaurant analysis and feature engineering.

Key activities included:

- Feature analysis
- Data transformation
- Restaurant attribute analysis
- Additional customer and restaurant insights

---

# Level 3

Level 3 focused on predictive modeling, customer preference analysis, and data visualization.

---

## 🔹 Task 1 – Predictive Modeling

The objective was to predict the **Aggregate Rating** of a restaurant using available features.

Three regression algorithms were tested:

1. Linear Regression
2. Decision Tree Regressor
3. Random Forest Regressor

### Model Performance

| Model | MAE | MSE | RMSE | R² Score |
|---|---:|---:|---:|---:|
| Linear Regression | 0.9799 | 1.4788 | 1.2161 | 0.3503 |
| Decision Tree | 0.2212 | 0.1156 | 0.3400 | 0.9492 |
| Random Forest | 0.1957 | 0.0915 | 0.3024 | 0.9598 |

The Random Forest model produced the lowest error values and highest R² score among the tested models on the test set.

---

## 🔹 Task 2 – Customer Preference Analysis

Cuisine preferences were analyzed using customer votes and restaurant ratings.

### Most Popular Cuisines by Total Votes

| Cuisine | Total Votes |
|---|---:|
| North Indian | 595,981 |
| Chinese | 364,351 |
| Italian | 329,265 |
| Continental | 288,255 |
| Fast Food | 184,058 |

North Indian cuisine received the highest total number of votes in the dataset.

### Higher-Rated Cuisines

For a more reliable comparison, cuisines with at least 50 restaurants were considered.

| Cuisine | Average Rating |
|---|---:|
| Sandwich | 4.07 |
| Steak | 3.99 |
| Sushi | 3.97 |
| Mediterranean | 3.95 |
| Indian | 3.92 |

The analysis demonstrates that customer popularity and average rating are different measures.

---

## 🔹 Task 3 – Data Visualization

The following visualizations were created:

- Restaurant rating distribution
- Rating-wise restaurant count
- Top cuisines by average rating
- Top cuisines by customer votes
- Votes vs Aggregate Rating relationship
- City-wise average rating

### Visualization Files

The generated charts are available in:

`Level 3/task3_visualizations/`

---

# 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Scikit-learn
- Machine Learning
- Data Analysis
- Data Visualization

---

# 📂 Project Structure

```text
Cognifyz/
│
├── Level 1/
├── Level 2/
├── Level 3/
│   ├── task1.py
│   ├── task2.py
│   ├── task3.py
│   ├── task1_model_comparison.csv
│   ├── task2_popular_cuisines.csv
│   ├── task2_higher_rated_cuisines.csv
│   └── task3_visualizations/
│
└── README.md
```

---

# 📈 Key Learning Outcomes

Through this project, I gained practical experience in:

- Exploratory Data Analysis
- Data Cleaning
- Feature Selection
- Categorical Encoding
- Regression Modeling
- Model Evaluation
- Customer Preference Analysis
- Data Visualization
- Interpreting analytical results
- Organizing a data analytics project for GitHub

---

## 👤 Author

**Pramada Katkar**

B.Sc. Data Science  
Savitribai Phule Pune University

---

## 📌 Conclusion

The Cognifyz Restaurant Data Analysis project provided practical experience in applying data analysis and machine learning techniques to a real-world restaurant dataset. The project demonstrates the complete workflow from data exploration and preprocessing to predictive modeling, customer preference analysis, and visualization.
