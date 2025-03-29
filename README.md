# mental-health-analysis
Student Mental Health Risk Analysis Project (DSC510)

# Mental Health Risk Analysis for University Students

This project analyzes mental health risk among Gen Z university students using survey data, with the goal of identifying undiagnosed high-risk individuals and improving access to treatment through data-driven insights and interventions.

📊 **Dashboard Link:** [View Interactive Tableau Dashboard](https://public.tableau.com/views/dsc510_draft/Finalized?:language=zh-TW)

---

## 📌 Project Overview

With the increase of depression and anxiety among younger generation, early detection is important. This project analyzes self-reported mental health survey data (PHQ-9, GAD-7, ACHA Well-being, and self reported general health) from U.S. college students to classify risk levels and recommend intervention strategies. We focused on Generation Z students (born 1997–2012) and explored treatment gaps, high-risk populations, and racial/geographic disparities.

---

## 🛠️ Tools & Technologies
- Excel
- Python
- Tableau Public
- Data cleaning & preprocessing
- Classification modeling
- Correlation and feature importance analysis

---

## 🔍 Methodology

- Cleaned and transformed survey data (581 rows × 129 columns)
- Focused on Gen Z respondents
- Converted categorical variables to numerical
- Created composite scores for PHQ-9, GAD-7
- Labeled risk levels (Low / Moderate / High)
- Built classification model (XGBoost) to identify key features
- Visualized findings with Tableau dashboard

---

## 📈 Key Findings

- **69.33%** of students were undiagnosed, highlighting a gap in mental health services.
- Over **50%** of students were in the Moderate to High Risk category.
- Emotional indicators like **“Felt very sad”** and **“Felt too depressed to function”** were strong predictors of high risk.
- **Racial and state-level disparities** exist: Black students and those in urban states (CA, NY) were overrepresented in high-risk, untreated groups.
- Many high-risk students **perceive themselves as healthy**, showing a self-awareness gap.

---

## 💡 Intervention Recommendations

- Expand virtual mental health access (e.g., 24/7 counseling)
- Address racial disparities with culturally sensitive programs
- Promote self-screening and mental health awareness campaigns
- Train university staff in mental health response (e.g., Be REAL program)

---

## 👤 Author Contribution

This was a team project for DSC 510 (Winter 2024–2025).  
**My role**: Data cleaning, PHQ-9/GAD-7 scoring logic, risk labeling, XGBoost modeling, and Tableau dashboard design.

---

## 📂 Files
- `notebooks/`: Jupyter Notebook with data cleaning and model training
- `images/`: Key graphs and dashboard screenshots
- `report.pdf`: Final project report (full context and methodology)

---

## 🗃️ Data Source
OpenICPSR mental health survey dataset (publicly available)

---

## 🧠 Future Work
- Expand predictive modeling to include more factors (e.g., lifestyle)
- Implement time-based trend analysis for university dashboards
- Develop mental health monitoring tools based on survey logic
