# 📌 Project Title
**Analyzing Lung Cancer Risk Factors to Support Early Detection and Public Health Awareness**

### 📁 Prepared by
**Tolulope Emuleomo (The Data Profesor)**

---

## 🧾 Introduction

Lung cancer remains one of the most fatal cancers worldwide, primarily due to late-stage detection. This project explores a clinical and lifestyle dataset of 890,000 individuals across 27 European countries from 2014–2024. The goal is to identify patterns, risk factors, and actionable insights that can inform public health awareness campaigns and early screening strategies.

---

## 🧹 Data Cleaning and Preparation

### ✅ Steps Taken:
- **No duplicates** or **missing values** were found.
- **Age grouped** into: Child (4–12), Teenage (13–19), Youth (20–35), Adult (36–59), Old (60–104).
- **Dates formatted** to ISO standard (`YYYY-MM-DD`) and **treatment days** calculated.
- **Binary columns** (`0/1`) converted to `"Yes"`/`"No"` and `"Survived"`/`"Not Survived"` for interpretability:
  - `family_history`, `hypertension`, `asthma`, `cirrhosis`, `other_cancer`, `survived`.

---

## 🔍 Exploratory Analysis & Key Findings

### 📊 Demographic & Clinical Insights:
- **Adults (36–59)** and **older adults (60–104)** account for 97% of cases.
- **Gender** split: 50.02% Male, 49.98% Female.
- **Smoking status** is evenly distributed across:
  - Never, Former, Passive, and Current Smokers (~222k each).
- **Comorbidities**:
  - Hypertension: 75% of patients
  - Asthma: 47%
  - Cirrhosis: 23%
- **Cancer stages** are evenly distributed (Stages I–IV ~222k each).
- **Balanced data** from 27 countries and across 11 years.

---

## 🧠 Key Insights

- **Passive smoking** is just as prevalent as active smoking.
- **Comorbid conditions** (hypertension, asthma) may significantly increase risk.
- **Family history** is present in 50% of cases — an important genetic factor.
- **Screening seems focused** on adults, but under-18s and young adults are underrepresented.
- **Even cancer staging** suggests early detection is achievable, though not universal.

---

## 📣 Public Health Strategy Recommendations

1. **Expand Awareness to Include Passive Smokers**  
   Highlight secondhand smoke risks in urban environments.

2. **Promote Screening in Midlife (35+)**  
   Encourage routine screening from age 35, even if asymptomatic.

3. **Target Comorbid Populations**  
   Focus on individuals with hypertension, asthma, or cirrhosis for early screening.

4. **Leverage Family History in Screening**  
   Use family history assessments in primary care.

5. **Develop Region-Specific Campaigns**  
   Customize awareness strategies based on country-specific habits and culture.

---
