# Insurance-Cost-Prediction-Analysis
"End-to-end Insurance Cost Prediction project involving EDA, statistical testing, feature engineering, data preprocessing, and machine learning using Python and Scikit-Learn to analyze and predict medical insurance charges."


---

# 📖 Project Overview

Healthcare insurance costs vary significantly among individuals due to multiple demographic and lifestyle factors. Understanding these factors can help insurance providers make informed pricing decisions and better assess customer risk.

In this project, I performed comprehensive data analysis, statistical testing, feature engineering, and machine learning to uncover key insights and predict insurance charges.

The project demonstrates the complete Data Science workflow from raw data exploration to predictive modeling.

---

# 🎯 Business Problem

Insurance companies need accurate estimates of future medical expenses to determine appropriate premiums.

The objective of this project is to:

* Analyze customer demographics and health-related attributes.
* Identify factors influencing insurance charges.
* Discover hidden patterns using statistical analysis.
* Build a machine learning model capable of predicting insurance costs.

---

# 📊 Dataset Information

The dataset contains information about insurance policyholders.

| Feature  | Description                   |
| -------- | ----------------------------- |
| age      | Age of the insured individual |
| sex      | Gender                        |
| bmi      | Body Mass Index               |
| children | Number of dependents covered  |
| smoker   | Smoking status                |
| region   | Residential region            |
| charges  | Medical insurance cost        |

### Target Variable

🎯 **charges**

---

# 🛠️ Tech Stack

### Programming Language

* Python

### Libraries

* Pandas
* NumPy
* Matplotlib
* Seaborn
* SciPy
* Scikit-Learn

### Environment

* Jupyter Notebook

---

# 🔄 Project Workflow

## 1. Data Understanding

* Dataset exploration
* Data types inspection
* Statistical summary
* Shape analysis
* Feature understanding

---

## 2. Data Cleaning

* Checked missing values
* Verified duplicate records
* Data quality validation
* Feature consistency checks

---

## 3. Exploratory Data Analysis (EDA)

Performed detailed visual analysis using:

### Univariate Analysis

* Histograms
* Distribution plots
* Count plots

### Bivariate Analysis

* Age vs Charges
* BMI vs Charges
* Smoker vs Charges
* Gender vs Charges

### Multivariate Analysis

* Correlation Heatmap
* Feature relationship analysis

---

## 4. Statistical Analysis

Applied statistical techniques to validate assumptions and relationships.

### Chi-Square Test

Used to determine whether categorical variables significantly impact insurance charges.

Key objective:

* Identify statistically significant features.
* Understand dependency relationships between variables.

---

## 5. Feature Engineering

Implemented:

* Charge categorization using quantile binning
* Feature preparation for statistical testing
* Encoding categorical variables

---

## 6. Machine Learning

### Model Used

✅ Linear Regression

### Steps Performed

* Data Splitting
* Model Training
* Prediction
* Performance Evaluation

---

# 📈 Key Insights

### 🚬 Smoking Significantly Increases Charges

Smokers incur substantially higher medical costs compared to non-smokers.

### 📊 BMI Impacts Insurance Costs

Individuals with higher BMI values generally tend to have increased insurance expenses.

### 👥 Age Plays an Important Role

Insurance charges tend to increase with age.

### 🌍 Region Has Limited Impact

Residential region shows comparatively smaller influence on charges.

### 👨‍👩‍👧 Children Have Moderate Effect

Number of dependents contributes slightly to overall charges.

---

# 🤖 Machine Learning Model

### Linear Regression

The model learns relationships between customer attributes and insurance charges.

### Inputs

* Age
* Sex
* BMI
* Children
* Smoker
* Region

### Output

* Predicted Insurance Charges

---

# 📊 Business Value

This solution can help:

### Insurance Companies

* Estimate customer risk
* Improve premium pricing
* Identify high-risk customers
* Support underwriting decisions

### Data Teams

* Understand cost drivers
* Generate business insights
* Support strategic planning

---

# 📷 Visualizations Included

✔ Distribution Analysis

✔ Count Plots

✔ Box Plots

✔ Correlation Heatmaps

✔ Statistical Testing Results

✔ Feature Relationship Analysis

---

# 📁 Project Structure

```text
Insurance-Cost-Prediction/
│
├── insurance.ipynb
├── insurance.csv
├── README.md
│
├── images/
│   ├── heatmap.png
│   ├── distribution.png
│   └── boxplot.png
│
└── requirements.txt
```

---

# 🚀 Future Enhancements

* Random Forest Regressor
* XGBoost Regressor
* Hyperparameter Tuning
* Feature Selection
* Streamlit Deployment
* Power BI Dashboard Integration
* Advanced Model Comparison

---

# 💡 Skills Demonstrated

### Data Analytics

* Data Cleaning
* Data Visualization
* Exploratory Data Analysis
* Statistical Testing

### Machine Learning

* Feature Engineering
* Linear Regression
* Model Evaluation

### Business Understanding

* Problem Solving
* Insight Generation
* Data-Driven Decision Making

---

# 🎓 Learning Source & Acknowledgements

This project was completed as part of my Data Science learning journey under the guidance of Akarsh Vyas through Sheryians AI School.

Special thanks for providing practical, industry-oriented guidance in:

* Data Analytics
* Statistics
* Machine Learning
* Real-world Project Development

While inspired by concepts taught during the course, all implementation, analysis, visualizations, and documentation were completed independently as part of hands-on learning and portfolio development.

---

# 👩‍💻 Author

## Riya Talele

**Aspiring Data Scientist | Data Analyst | AI & ML Enthusiast**

Passionate about transforming raw data into meaningful insights through analytics, visualization, and machine learning.

### Connect With Me

* LinkedIn: *Add your LinkedIn profile link*
* GitHub: *Add your GitHub profile link*

---

# ⭐ Support

If you found this project useful, consider giving it a **Star ⭐** on GitHub.

It motivates me to build and share more Data Analytics and Data Science projects.

---



