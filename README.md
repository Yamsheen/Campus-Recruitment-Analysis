# Campus-Recruitment-Analysis

# Unveiling the Roadmap to Success: Campus Recruitment Analysis

This project explores the influential determinants shaping career pathways and job prospects using a campus recruitment dataset. It utilizes Exploratory Data Analysis (EDA), statistical testing, and Machine Learning to predict employment outcomes and estimate salary levels.

##  Project Overview
The goal of this research is to understand how variables like academic performance, gender, and work experience influence recruitment outcomes. 

### Key Research Questions:
1. **Employment Prediction:** Which factors significantly impact whether a candidate gets placed?
2. **Salary Estimation:** How do different variables correlate with the salary offered?
3. **Gender Bias Analysis:** Are there prevalent disparities in employment rates or salaries between genders?

##  Dataset
The dataset was sourced from **Kaggle (Ben Roshan D)** and contains records of student placements including academic percentages (10th, 12th, Degree, MBA), specializations, work experience, and salary offers.

##  Key Findings & Methodology
- **Academic Excellence:** High secondary education percentages (`ssc_p`) were found to be the most significant predictor of placement.
- **Work Experience:** Students with prior work experience showed significantly higher placement rates.
- **Modeling Results:**
  - **Classification:** A Multi-Layer Perceptron (MLP) achieved the highest accuracy of **83.3%** for predicting placement status.
  - **Regression:** Support Vector Regression (SVR) performed best for salary estimation with a Mean Absolute Percentage Error (MAPE) of **14.88%**.
- **Gender Insights:** While a wage gap was observed (males generally receiving higher offers), statistical tests (ANOVA/Chi-Square) did not show a conclusive, statistically significant gender bias within this specific small dataset.

##  Tech Stack
- **Languages:** Python
- **Libraries:** Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn, Scipy, Statsmodels
- **Models:** Random Forest, Logistic Regression, MLP, SVR, Gradient Boosting

##  File Descriptions
- `notebooks/01_EDA_and_Visualizations.ipynb`: Contains the code for all descriptive statistics and trend visualizations.
- `notebooks/02_Placement_Prediction.ipynb`: Focuses on RQ1 and RQ3 using classification models and Chi-square tests.
- `notebooks/03_Salary_Estimation.ipynb`: Focuses on RQ2 using regression models and ANOVA tests.

## 🔗 Original Article
For a detailed walkthrough of the analysis and insights, read my full article on [Medium](https://medium.com/@yamsheensaqib/unveiling-the-roadmap-to-success-exploring-influential-determinants-shaping-career-pathways-and-f6574b2987e6).