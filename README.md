# 🩺 Maternal Health Data Analysis

## 🔍 Overview

This project presents an in-depth analysis of maternal health data, focusing on identifying key factors that influence pregnancy outcomes. The study explores correlations between maternal health metrics—such as body fat, BMI, blood pressure, and substance use—and complications like gestational diabetes, preeclampsia, preterm births, and delivery methods.

The goal is to provide actionable insights that can help in early detection of risks and promote better maternal and neonatal care.

---

## 📦 Dataset Summary

- **Source:** Low-risk outpatient clinic  
- **Time Frame:** October 2016 – December 2017  
- **Sample Size:** 211 patients (originally 272)  
- **Features:** 116 variables including demographics, ultrasound, lab tests, nutrition, and delivery details

### Key Features Include:

- Maternal abdominal fat (visceral and subcutaneous)
- Ultrasound biometry and fetal growth indicators
- Lab test results (glucose, lipids, etc.)
- Pregnancy outcomes (GDM, birth weight, NICU, delivery mode)
- Lifestyle factors (smoking, alcohol, drug use)

---

## 🛠 Technologies & Tools

| Tool           | Purpose                          |
|----------------|----------------------------------|
| PostgreSQL     | Data cleaning and transformation |
| SQL / DAX      | Querying and metrics             |
| Power BI       | Interactive dashboards           |
| Python (optional) | Data preprocessing & EDA     |

---

## 🧼 Data Preparation

The dataset underwent several cleaning and preprocessing steps:

- Handled missing values using domain-informed imputation
- Normalized categorical fields (e.g., delivery type, medication usage)
- Converted column types for better querying
- Removed outliers based on clinical plausibility

---

## 📈 Exploratory Analysis & Insights

### 📌 Abdominal Fat & Pregnancy Outcomes
- Higher visceral fat is significantly linked to increased rates of **gestational diabetes**, **preeclampsia**, and **C-section** deliveries.

### 📌 Substance Use
- Women who reported **alcohol, tobacco, or drug use** had elevated fat percentages and were more prone to **hypertension** and **preterm labor**.

### 📌 BMI and Blood Pressure
- Elevated **pre-pregnancy BMI** shows strong correlation with **high systolic blood pressure**, influencing both maternal and fetal risks.

### 📌 Waist-to-Hip Ratio (WHR)
- A WHR above clinical threshold is associated with **preterm births**, **NICU admissions**, and **gestational complications**.

### 📌 Delivery Mode
- Women with body fat above 45% had a higher probability of **C-section**, reinforcing the link between body composition and delivery outcomes.

---

## 📊 Visualizations

Interactive Power BI dashboards were created to visualize:

- Distribution of fat levels across patients
- Comparison of complication rates by BMI and WHR
- Delivery methods based on maternal health indicators
- Time-series view of health parameters

(Include screenshots or dashboard links here)

---

## ✅ Conclusion

This project reinforces the importance of managing maternal weight, especially abdominal fat, to reduce the likelihood of adverse pregnancy outcomes. It also highlights how **preventive counseling and early detection** can improve outcomes for both mothers and newborns.

---

## 📁 Repository Structure

```
/maternal-health-analysis
│
├── data/                   # Raw and cleaned datasets
├── notebooks/              # Jupyter notebooks (optional)
├── powerbi/                # Power BI .pbix files or images
├── sql/                    # SQL queries and data prep scripts
├── README.md               # Project documentation (this file)
```

---

## 📬 Contact

For questions or collaborations, feel free to open an issue or connect via LinkedIn.

