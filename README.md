# Patient_Dashboard_Project_1
# 🏥 Patient Health Analytics Dashboard — Power BI

## 📌 Project Overview
A comprehensive, multi-page interactive healthcare analytics dashboard 
built in Power BI, analyzing 1,000 simulated patient records across 
37 clinical, demographic, financial, and lifestyle attributes.

## 🎯 Objective
To transform raw patient data into actionable health insights through 
interactive visualizations, enabling data-driven decisions across 
clinical, operational, and financial domains.

## 📊 Dashboard Pages
| Page | Focus Area |
|------|-----------|
| 1️⃣ Patient Overview      | KPIs, demographics, geographic distribution |
| 2️⃣ Clinical Insights     | Diagnoses, departments, readmission analysis |
| 3️⃣ Vitals & Lab Analytics| BP trends, BMI, HbA1c, glucose risk mapping  |
| 4️⃣ Financial & Operations| Cost analysis, insurance, admission trends   |
| 5️⃣ Lifestyle & Risk      | Smoking, alcohol, exercise, risk scoring     |

## 🗂️ Dataset
- 1,000 synthetic patient records (Python-generated)
- 37 features including vitals, labs, diagnoses, costs & lifestyle
- Tools used: Python (NumPy, Pandas, OpenPyXL), Power BI Desktop

## 🔧 Tech Stack
- **Data Generation:** Python (Pandas, NumPy, OpenPyXL)
- **Data Visualization:** Microsoft Power BI Desktop
- **Data Modeling:** DAX Measures, Calculated Columns
- **File Format:** Excel (.xlsx) → Power BI (.pbix)

## 📐 Key Features
- ✅ 5 fully interactive dashboard pages
- ✅ 20+ DAX measures and calculated columns
- ✅ Dynamic slicers and cross-filtering
- ✅ Conditional formatting and risk color coding
- ✅ Drill-through to patient-level detail
- ✅ KPI cards, scatter plots, heatmaps, maps & trend lines
- ✅ Risk scoring model (Smoking + Alcohol + Exercise + BMI)

## 📈 Key Insights Uncovered
- Hypertension and Diabetes are the top primary diagnoses
- Sedentary patients have significantly higher average BMI
- ICU costs are 3x higher in Cardiology vs other departments
- Self-Pay patients show the lowest satisfaction scores
- HbA1c ≥ 6.5 correlates strongly with elevated glucose levels

## 🚀 How to Use
1. Clone this repository
2. Open `Patient_Dataset_1000.xlsx` in Power BI Desktop
3. Load the `.pbix` file
4. Interact with slicers and drill-throughs

## 📁 Files
- `Patient_Dataset_1000.xlsx` — Source dataset
- `HealthDashboard.pbix` — Power BI Dashboard file
- `README.md` — Project documentation

---
⭐ If you found this useful, please star the repository!
