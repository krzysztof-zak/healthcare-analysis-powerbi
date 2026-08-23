# Healthcare Analysis Dashboard | Power BI

## 📊 Project Overview

This project presents an interactive **Healthcare Analysis Dashboard** built in **Power BI**. The purpose of the report is to analyze hospital performance and patient discharge data, with a particular focus on operational efficiency, healthcare costs, and patient length of stay.

The dashboard enables users to compare hospitals and healthcare service areas, identify differences in performance, and explore factors that may influence hospital costs and patient outcomes.

---

## 🎯 Business Questions

The analysis aims to answer questions such as:

- Which hospitals have the highest and lowest Average Length of Stay?
- How do hospitals compare in terms of Average Cost per Discharge?
- Which factors influence the Length of Stay?
- How does patient severity affect hospital discharges?
- How do healthcare costs and Length of Stay vary across hospitals?
- How does an individual hospital perform compared to the overall average?

---

## 📄 Dashboard Pages

### 🏠 Home

The landing page provides navigation to the main sections of the report.

### ⏱️ LOS Comparison

This page focuses on comparing hospitals based on **Length of Stay (LOS)** and operational metrics.

Key metrics include:

- Average Length of Stay
- Total Discharges
- Total Surgeons
- Number of Hospitals
- Variance from the overall average

The page also includes a **Key Influencers** analysis to identify factors that may contribute to differences in patient Length of Stay.

### 💰 Cost Comparison

This page analyzes healthcare costs and hospital efficiency.

Key metrics include:

- Average Cost per Discharge
- Average Length of Stay
- Total Discharges
- Hospital comparisons
- Healthcare Service Area analysis

A scatter plot is used to explore the relationship between:

- Average Cost per Discharge
- Average Length of Stay
- Number of Discharges

### 🏥 Hospital Profile

This page provides a detailed profile of a selected hospital.

The analysis includes:

- Average Length of Stay compared with the overall average
- Average Cost per Discharge compared with the overall average
- Discharges by Severity of Illness
- Discharges by Risk of Mortality
- Diagnosis distribution
- Patient Disposition

---

## 📈 Key KPIs

The dashboard includes the following key performance indicators:

- **Total Discharges**
- **Total Hospitals**
- **Total Surgeons**
- **Average Length of Stay**
- **Average Cost per Discharge**
- **Variance from Average**
- **Percentage Variance**

---

## 🛠️ Tools & Technologies

- **Power BI**
- **Power Query**
- **DAX**
- **Data Modeling**
- **Data Visualization**

---

## 🔍 Key Features

- Interactive hospital selection
- Dynamic filtering
- Hospital performance comparison
- Length of Stay analysis
- Healthcare cost analysis
- Key Influencers analysis
- Scatter plot analysis
- Dynamic hospital profiles
- Variance analysis
- Interactive navigation between report pages

---

## 📂 Repository Structure

```text
healthcare-analysis-powerbi/
│
├── Healthcare analysis.pbix
│
├── screenshots/
│   ├── home.png
│   ├── los-comparison.png
│   ├── cost-comparison.png
│   └── hospital-profile.png
│
└── README.md
