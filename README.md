# PRODIGY_DS_02 - Data Cleaning and Exploratory Data Analysis (EDA) on the Titanic Dataset

### 📌 Objective
The objective of this project is to perform **Data Cleaning** and **Exploratory Data Analysis (EDA)** on the Titanic dataset to uncover meaningful patterns, trends, and relationships among various passenger attributes and survival outcomes.

---

## 📂 Dataset

- **Dataset:** Titanic Dataset
- **Source:** Kaggle Titanic - Machine Learning from Disaster
- **Files Used:**
  - train.csv
  - test.csv

---

## 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook

---

## 📋 Data Cleaning

The following preprocessing steps were performed:

- Checked dataset structure and data types.
- Identified missing values.
- Filled missing values in:
  - **Age** using the median value.
  - **Embarked** using the mode.
  - **Fare** using the median (if required).
- Removed the **Cabin** column due to a large number of missing values.
- Checked and removed duplicate records.
- Verified the dataset after cleaning.

---

## 📊 Exploratory Data Analysis

The following visualizations were created:

- Survival Count
- Survival by Gender
- Survival by Passenger Class
- Age Distribution
- Fare Distribution
- Age vs Survival (Box Plot)
- Correlation Heatmap
- Pair Plot

---

## 📈 Key Findings

- Female passengers had a significantly higher survival rate than male passengers.
- Passengers traveling in First Class were more likely to survive than those in Second and Third Class.
- Most passengers were between 20 and 40 years of age.
- Higher ticket fares were generally associated with better survival chances.
- Passenger class and gender were the strongest factors influencing survival.

---

## 📁 Project Structure

```
PRODIGY_DS_02/
│── train.csv
│── test.csv
│── Titanic_EDA.ipynb
│── README.md
│── requirements.txt
└── images/
    ├── survival_count.png
    ├── survival_by_gender.png
    ├── survival_by_class.png
    ├── age_distribution.png
    ├── fare_distribution.png
    ├── age_vs_survival.png
    ├── correlation_heatmap.png
    └── pairplot.png
```

---

## ▶️ How to Run

1. Clone the repository.
2. Install the required libraries:

```bash
pip install -r requirements.txt
```

3. Open the Jupyter Notebook.

4. Run all cells to perform data cleaning and exploratory data analysis.

---

## 🎯 Conclusion

This project demonstrates the complete workflow of cleaning and analyzing the Titanic dataset using Python. Through exploratory data analysis, meaningful insights were obtained regarding passenger survival. The analysis revealed that gender, passenger class, and ticket fare played significant roles in determining survival, while appropriate data preprocessing ensured reliable and accurate results.

---

## 👩‍💻 Author

**Sara Bhosale**

Artificial Intelligence & Data Science Student

Prodigy InfoTech Data Science Intern
