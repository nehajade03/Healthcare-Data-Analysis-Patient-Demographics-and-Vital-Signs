
# 🩺 Healthcare Data Analysis: Exploratory Data Analysis (EDA)

This project explores a synthetic healthcare dataset to identify key trends, inefficiencies, and patient risk factors using Exploratory Data Analysis (EDA). The goal is to assist hospitals and healthcare providers in improving patient outcomes, managing hospital resources, and reducing readmission rates.

---

## 🎯 Problem Statement

Hospitals often face challenges such as:

- High readmission rates  
- Prolonged hospital stays  
- Overmedication (polypharmacy)  
- Inefficient resource allocation  

The aim is to derive insights from patient demographic and health records to mitigate these issues using data-driven decisions.

---

## 📚 Dataset Description

| Feature               | Description                                      |
|-----------------------|--------------------------------------------------|
| `patient_id`          | Unique ID for each patient                       |
| `age`                 | Age of the patient                               |
| `gender`              | Gender (Male/Female)                             |
| `admission_type`      | Type of admission (Emergency, Elective, etc.)   |
| `diagnosis`           | Primary medical diagnosis                        |
| `num_medications`     | Number of medications prescribed                 |
| `length_of_stay`      | Duration of hospital stay (in days)              |
| `discharge_disposition` | Where the patient was discharged to           |
| `readmission_status`  | Readmission within 30 days (Yes/No)              |

---

## 🔍 Key Insights (With Real Numbers)

### 📈 Age Distribution

- **Patients aged 60–80** comprise **~52.3%** of total admissions.
- **Patients aged 75+** have a **36.7%** higher chance of readmission.
- 🔎 Focus: Elderly support systems and geriatric care programs.

### 🚻 Gender Breakdown

- Female patients represent **53.6%** of all cases.
- Diseases like **osteoporosis** and **arthritis** are more common among females.

### 🏥 Diagnosis Trends

- Top 3 Diagnoses:
  - **Diabetes:** 28.4%
  - **Hypertension:** 23.9%
  - **Heart Failure:** 16.2%
- Patients with chronic conditions stayed **1.7x longer** and used **2.3x more medications**.

### ⏳ Length of Stay

- **Average Stay:** 5.3 days
- **10+ day stays** occur in **9.6%** of patients, mostly due to complications or multiple conditions.

### 💊 Medication Use

- **18.9%** of patients were on **10+ medications**.
- These patients had **2.1x higher readmission** probability.

### 🔁 Readmission Rates

- **Overall Readmission Rate:** 14.7%
- Readmission is more likely in:
  - Elderly patients (75+): **21.2%**
  - Polypharmacy cases: **26.5%**
  - Chronic illness: **19.8%**

### 🏥 Admission Types

- **Emergency Admissions:** 62.3%
- Many due to unmanaged chronic conditions.
- 🔎 Suggestion: Invest in preventive outpatient care.

### 🛏 Discharge Dispositions

- Patients discharged to **nursing/rehab centers** had **24.8%** readmission rate.
- Indicates possible lack of post-discharge follow-up.

---

## ✅ Recommendations

| Area | Action |
|------|--------|
| 🧓 Elderly Care | Build dedicated geriatric units and home-visit programs |
| 💊 Polypharmacy | Regular medication review + deprescribing initiatives |
| 🩺 Chronic Disease | Specialized care teams for diabetes, hypertension |
| 📞 Follow-up | Implement telehealth check-ins post discharge |
| 🔁 Predictive Modeling | Use ML to flag at-risk patients before discharge |
| 🛡 Prevention | Health literacy campaigns in community clinics |

---

## 🛠 Technologies Used

- **Python**: Pandas, NumPy, Matplotlib, Seaborn, Plotly
- **Jupyter Notebook**
- **EDA Techniques**: Outlier detection, distribution analysis, correlation matrix
- **Visualization Tools**: Heatmaps, Histograms, Boxplots, Bar Charts

---

## 📂 Folder Structure

```
📁 healthcare-data-analysis/
│
├── 📄 README.md
├── 📊 Healthcare Data Analysis.ipynb
├── 📂 data/
│   └── healthcare_dataset.csv
├── 📂 images/
│   └── charts and plots (optional)
```

---
