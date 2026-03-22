# 🚢 Titanic Survival Analysis — Tableau Project

A data visualization project exploring survival patterns from the Titanic dataset using Tableau Public.

---

## 📊 Charts Built

### Chart 1 — Bar Chart: Survival by Sex
![Chart 1](screenshots/chart1_bar_sex.png)

- **Female survival rate: ~74%**
- **Male survival rate: ~19%**
- Females were nearly **4x more likely to survive** than males
- Confirms the historical **"women and children first"** evacuation policy

---

### Chart 2 — Line Chart: Survival by Age
![Chart 2](screenshots/chart2_line_age.png)

- **Children aged 0–9 had the highest survival rate (~61%)**
- Sharp drop in survival for ages **20–30** (young males, mostly 3rd class)
- Middle-aged passengers (30–50) had moderate survival (~40%)
- Age 80 spike is a statistical outlier (only 1 passenger)

---

### Chart 3 — Scatter Plot: Age vs Fare (colored by Survival)
![Chart 3](screenshots/chart3_scatter_age_fare.png)

- 🟠 **Orange = Survived | 🔵 Blue = Did not survive**
- Passengers with **higher fares (1st class) survived more**
- Most expensive tickets (~$512) — both passengers survived
- **Low fare passengers (3rd class)** had significantly lower survival
- Dense cluster of blue dots in the **low fare / age 20–40** range

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
```

---

## 🚀 How to Open the Tableau Workbook

1. Download and install [Tableau Public](https://public.tableau.com/en-us/s/download) (free)
2. Clone or download this repository
3. Open `TitanicAnalysis.twbx` in Tableau Public
4. Explore all 3 charts and the dashboard

---

## 👤 Author

- **GitHub:** your-username
- **Project:** Titanic Survival Analysis — Tableau Visualization

---

## 📜 License

This project is open source and available under the [MIT License](LICENSE).
