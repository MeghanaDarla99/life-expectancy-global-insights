#  Health and Development Indicators: Global Insights

This is an academic project completed as part of the *INFO-I 501: Introduction to Informatics* course in the **MS in Health Informatics** program at Indiana University Indianapolis, during the Fall 2023 semester (Aug-Dec 2023). The project explores global disparities in life expectancy using a dataset from Kaggle. Through data cleaning, visualization, and predictive modeling, we identified the strongest social and economic factors influencing health outcomes across countries.
---

##  Dataset

- **Source:** [Kaggle – Life Expectancy Data](https://www.kaggle.com/datasets/arunjangir245/life-expectancy-data)
- **File Used:** [`Life_Expectancy_Data.csv`](./data/Life_Expectancy_Data.csv)
- **Years Covered:** ~2000 to 2015  
- **Variables Analyzed:** Adult Mortality, Alcohol, Schooling, GDP, HIV/AIDS, BMI, Status (Developed/Developing), etc.

---

##  Models Implemented

- **Linear Regression**
- **Ridge Regression** (with GridSearchCV)
- **Decision Tree**
- **Random Forest**

---

##  Key Findings

- **Top Positive Correlates**: Schooling, Income composition of resources, BMI
- **Top Negative Correlates**: HIV/AIDS, Adult Mortality
- **Best Performing Model**: Random Forest (highest R² score, lowest RMSE)

---

##  Technologies Used

- Python (Jupyter Notebook)
- Pandas, NumPy, Seaborn, Scikit-learn, Matplotlib, Statsmodels
- SQL via phpMyAdmin (for initial data extraction)

---

##  Authors

- [Sushruthi Panakanti](https://github.com/psushruthi)
- [Meghana Darla](https://github.com/meghanadarla99)
- Sai Mahidhar Reddy
- Sudha Rani Yeruva
- Shamily Reddy

---

##  How to Run

1. Clone the repository:

```bash
git clone https://github.com/psushruthi/life-expectancy-global-insights.git

2. Install the required packages:
pip install -r requirements.txt

3. Open notebooks/Our_Project.ipynb in Jupyter Notebook and run all cells.

---

##  Acknowledgements

Special thanks to Professor Zeyana Hamid for her mentorship and guidance throughout this course and project.

---

##  License
This project is for academic and educational purposes only.
