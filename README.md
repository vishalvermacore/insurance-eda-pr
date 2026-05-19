# Insurance EDA & Linear Regression Project 📊

This project focuses on Exploratory Data Analysis (EDA), data preprocessing, and Machine Learning using a healthcare insurance dataset. The main objective of this project is to analyze patterns, trends, and relationships in the data and build a Linear Regression model to predict medical insurance charges.

---

# Project Overview

In this project, I performed:

- Exploratory Data Analysis (EDA)
- Data Cleaning & Preprocessing
- Data Visualization
- Feature Understanding
- Pattern & Trend Analysis
- Feature Encoding
- Linear Regression Model Building
- Model Training & Testing
- Model Evaluation

The dataset contains information related to:

- Age
- Gender
- BMI
- Smoking habits
- Region
- Number of children
- Insurance charges

---

# Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook

---

# Dataset Information

The dataset includes the following features:

| Feature | Description |
|--------|-------------|
| age | Age of the person |
| sex | Gender of the person |
| bmi | Body Mass Index |
| children | Number of children/dependents |
| smoker | Smoking status |
| region | Residential area |
| charges | Medical insurance charges |

---

# Exploratory Data Analysis (EDA)

During EDA, various visualizations and analyses were performed to understand the dataset.

## Analysis Performed

- Correlation Analysis
- Distribution Analysis
- Outlier Detection
- Categorical Feature Analysis
- Relationship Between Features
- Insurance Charge Analysis

---

# Key Insights

Some important insights discovered during analysis:

- Smoking significantly increases insurance charges
- BMI has a positive correlation with medical expenses
- Age affects insurance costs
- Smokers are charged much higher compared to non-smokers
- Data visualization helps identify patterns and outliers
- Lifestyle factors strongly influence medical insurance charges

---

# Data Preprocessing

The following preprocessing steps were performed:

- Handling missing values
- Label Encoding categorical columns
- Feature selection
- Splitting data into training and testing sets

---

# Machine Learning Model

After completing EDA and preprocessing, a Linear Regression model was built to predict insurance charges.

## Model Workflow

1. Import dataset
2. Encode categorical variables
3. Split dataset into train and test data
4. Train Linear Regression model
5. Predict insurance charges
6. Evaluate model performance

---
# Model Evaluation Metrics

The model was evaluated using:

- Mean Absolute Error (MAE)
- Mean Squared Error (MSE)
- R² Score

These metrics help measure the accuracy and performance of the regression model.

---

# Project Structure

```text
insurance-eda-project/
│
├── data/
│   └── insurance.csv
│
├── notebooks/
│   └── insurance_eda_analysis.ipynb
│
├── images/
│   ├── correlation_heatmap.png
│   ├── smoker_count.png
│   ├── gender_distribution.png
│   └── bmi_distribution.png
│
├── models/
│   └── linear_regression_model.pkl
│
├── README.md
├── requirements.txt
└── .gitignore
```

---

# Visualizations

## Correlation Heatmap

![Correlation Heatmap](images/correlation_heatmap.png)

---

## Smoker Count Distribution

![Smoker Count](images/smoker_count.png)

---

## Gender Distribution

![Gender Distribution](images/gender_distribution.png)

---

## BMI Distribution

![BMI Distribution](images/bmi_distribution.png)

---

# Future Improvements

- Feature Engineering
- Hyperparameter Tuning
- Advanced Regression Models
- Model Deployment
- Streamlit Dashboard
- Flask Web Application
- Advanced Statistical Analysis

---

# Learning Outcome

This project helped strengthen my understanding of:

- Data Analysis
- Exploratory Data Analysis (EDA)
- Data Visualization
- Data Preprocessing
- Machine Learning
- Regression Modeling
- Model Evaluation Techniques
- Working with real-world datasets

---

# Conclusion

This project demonstrates how Exploratory Data Analysis and Machine Learning techniques can be applied to healthcare insurance datasets to uncover valuable insights and predict insurance charges effectively using Linear Regression.
