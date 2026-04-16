# 🚢 Titanic Survival Analysis | EDA & Tableau Dashboard

---

## 📌 Project Overview  
This project explores the Titanic dataset using Python (Exploratory Data Analysis) and Tableau dashboards to understand the key factors that influenced passenger survival.

The analysis focuses on uncovering patterns related to gender, age, passenger class, and fare to provide meaningful insights into survival probability.

---

## 🎯 Objectives  
- Analyze survival patterns among passengers  
- Identify factors influencing survival rates  
- Perform data cleaning and exploratory data analysis (EDA)  
- Create interactive visualizations using Tableau  
- Present insights in a clear, business-friendly format  

---

## 🧰 Tools & Technologies  
- Python  
- Pandas  
- NumPy  
- Matplotlib  
- Seaborn  
- Tableau  
- Jupyter Notebook  

---

## 📊 Visualizations  
Includes:

- Survival distribution by gender  
- Age distribution analysis  
- Fare vs survival scatter plot  
- Class-based survival comparison  
- Tableau interactive dashboard  

---

## 📈 Key Insights  
- Females had a significantly higher survival rate compared to males  
- First-class passengers had better survival chances than lower classes  
- Younger passengers had higher survival probability in certain groups  
- Fare and passenger class showed a strong relationship with survival outcomes  

---

## 📊 Detailed Analysis

### Chart 1 — Survival by Sex  
- Female survival rate: ~74%  
- Male survival rate: ~19%  
- Women were significantly more likely to survive

---

### Chart 2 — Survival by Age  
- Children (0–9) had highest survival (~61%)  
- Ages 20–30 had lowest survival rate  
- Elderly passengers had mixed outcomes  

---

### Chart 3 — Age vs Fare (Scatter Plot)  
- Higher fare passengers had better survival rates  
- First-class passengers showed higher survival probability  
- Low fare passengers mostly did not survive  

---

## 🛠 Tools Used  
- Tableau Public  
- Python (Pandas, NumPy, Matplotlib, Seaborn)  
- Dataset: Titanic (Kaggle)  

---

## 📁 Repository Structure  
```txt
titanic-tableau-analysis/
├── README.md
├── Titanic-Dataset.csv
├── TitanicAnalysis.twbx
└── screenshots/
    ├── chart1_bar_sex.png
    ├── chart2_line_age.png
    ├── chart3_scatter_age_fare.png
    └── dashboard.png


## 📊 Charts Built & Analysis

---

### 📊 Chart 1 — Bar Chart: Survival by Sex  

<img width="588" height="467" alt="Survival by Sex" src="https://github.com/user-attachments/assets/51d5a260-3d26-41c3-86dc-59460cb728df" />

- Female survival rate: ~74%  
- Male survival rate: ~19%  
- Females were nearly **4x more likely to survive** than males  
- Confirms the historical **“women and children first”** evacuation policy  

---

### 📈 Chart 2 — Survival by Age  

<img width="675" height="461" alt="Survival by Age" src="https://github.com/user-attachments/assets/a37cc38d-9fb6-42e9-bfe3-305cb54eaf85" />

- Children (0–9 years) had the highest survival rate (~61%)  
- Sharp decline observed in ages 20–30 (majority male passengers in 3rd class)  
- Middle-aged group (30–50) showed moderate survival (~40%)  
- Age 80 spike is a statistical outlier (very small sample size)  

---

### 📊 Chart 3 — Scatter Plot: Age vs Fare (Survival Distribution)  

<img width="683" height="458" alt="Age vs Fare Survival" src="https://github.com/user-attachments/assets/cdbd22f2-69e2-47bd-af32-c75cba64de1d" />

- 🟠 Survived | 🔵 Did not survive  
- Higher fare passengers (1st class) had significantly higher survival rates  
- Highest fare (~$512) passengers all survived  
- Majority of low-fare passengers (3rd class) did not survive  
- Dense cluster of non-survivors appears in low fare (20–40 age group)  

---

## 🔍 Key Findings

| Factor | Finding |
|--------|---------|
| **Sex** | Females had 74% survival vs 19% for males |
| **Age** | Young children (0–9) had highest survival |
| **Fare/Class** | Higher fare = higher chance of survival |
| **Young Adults** | Ages 20–30 had the lowest survival overall |

---

## 🛠️ Tools Used

- **Tableau Public** — Data visualization
- **Dataset** — Titanic Dataset (CSV)
- **Fields used** — Survived, Sex, Age, Fare, Pclass

---

## 📁 Repository Structure

```
titanic-tableau-analysis/
│
├── README.md
├── Titanic-Dataset.csv
├── TitanicAnalysis.twbx        ← Tableau workbook
└── screenshots/
    ├── chart1_bar_sex.png
    ├── chart2_line_age.png
    ├── chart3_scatter_age_fare.png
    └── dashboard.png
```📁 Dataset

Titanic dataset (Kaggle)

👩‍💻 Author

Laxmi Rushaali Kuravi
M.S. Data Analytics | Business & Data Analyst

---

## 📜 License

This project is open source and available under the [MIT License](LICENSE).
