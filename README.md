## Health and Development Indicators: Global Insights

This is an academic project completed as part of the **INFO-I 501: Introduction to Informatics** course in the **MS in Health Informatics** program at Indiana University Indianapolis, during the Fall 2023 semester. The project investigates the key social and economic drivers of life expectancy across countries using statistical methods, data visualization, and machine learning models.

---

##  Dataset

- **Source:** [Kaggle – Life Expectancy Data](https://www.kaggle.com/datasets/arunjangir245/life-expectancy-data)
- **File Used:** [`Life_Expectancy_Data.csv`](./data/Life_Expectancy_Data.csv)
- **Years Covered:** 2000 to 2015  
- **Variables Analyzed:** Adult Mortality, Alcohol, Schooling, GDP, HIV/AIDS, BMI, Status (Developed/Developing), etc.

---

##  Methodology

We followed a structured 4-stage workflow:

1. **Data Collection & Extraction**  
   - Extracted and imported `.csv` data via **phpMyAdmin**  
   - Selected variables based on relevance to global health determinants

2. **Data Preprocessing**  
   - Outlier detection and capping using **IQR**
   - Normality tests using **Shapiro-Wilk**
   - Data normalization using **StandardScaler**
   - One-hot encoding of categorical variables

3. **Statistical Analysis**  
   - Non-parametric tests: **Mann-Whitney U**, **Kruskal-Wallis**
   - Correlation analysis: **Kendall Tau**, correlation matrix and heatmap

4. **Machine Learning Models**  
   - **Linear Regression**: Weak fit, high error  
   - **Ridge Regression**: Regularized model with optimized α using **GridSearchCV**  
   - **Decision Tree**: Handled non-linear patterns effectively  
   - **Random Forest**: Outperformed all others with best predictive accuracy

---

##  Tools & Technologies

- **Languages:** Python, SQL  
- **Libraries:** Pandas, NumPy, Seaborn, Scikit-learn, Matplotlib, Statsmodels  
- **Platforms:** Jupyter Notebook, phpMyAdmin  
- **Statistical Tests:** Shapiro-Wilk, Mann-Whitney U, Kruskal-Wallis, Kendall Tau

---

##  Key Insights

- **Strong Positive Correlations**:  
  - Income composition of resources  
  - Schooling  
  - BMI

- **Strong Negative Correlations**:  
  - HIV/AIDS prevalence  
  - Adult mortality

- **Best Performing Model**:  
  - **Random Forest**  
    - High R², low RMSE  
    - Robust to non-linearities and variable interactions

- **Policy Implication**:  
  Investments in education, nutrition, and income equity could significantly extend global life expectancy.

---

##  Authors

- [Sushruthi Panakanti](https://github.com/psushruthi)
- [Meghana Darla](https://github.com/meghanadarla99)
- Sai Mahidhar Reddy
- Sudha Rani Yeruva
- Shamily Reddy

---

##  Acknowledgements

Special thanks to Professor Zeyana Hamid for her mentorship and guidance throughout this course and project.

---

##  License

This project is for academic and educational purposes only.

---

## Contact

For questions or suggestions, please contact [Sushruthi Panakanti](https://github.com/psushruthi) at spanakan@iu.edu

Thank you.

---
