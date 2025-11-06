# 🏥 Healthcare Industry Dynamics Analysis (2019–2020)

An interactive **Power BI analytics project** that provides deep insights into the U.S. healthcare landscape from **2019–2020**, focusing on **hospital performance**, **patient outcomes**, **payer-provider dynamics**, and **financial efficiency**.  
The project leverages **Power BI**, **DAX**, and **Power Query** to build a data-driven dashboard that empowers healthcare stakeholders with actionable insights.

---

## 📊 Project Overview

The **Healthcare Industry Dynamics Dashboard** presents an in-depth analysis of U.S. healthcare data through intuitive and interactive visualizations.  
It decodes relationships between patients, hospitals, providers, and payers — helping identify patterns, optimize costs, and enhance healthcare delivery.

---

## 🎯 Objectives

- Analyze **key healthcare KPIs** such as total patients, insurance revenue, and operational costs.  
- Explore **hospital performance metrics** (AR, IPTP, and ARGE ratios).  
- Examine **payer-provider financial interactions** and revenue flow.  
- Visualize **patient demographics and lifestyle factors** affecting outcomes.  
- Enable **data-driven decision-making** for healthcare optimization.

---

## 🧱 Data Model (Star Schema)

The Power BI data model follows a **star schema** with one central **Fact Table** and multiple **Dimension Tables** for efficient querying and analysis.

**Fact Table:**
- Contains financial and operational measures (Revenue, Expenses, Adjustments, CPT Units, etc.)

**Dimension Tables:**
- `DimHospital` – Hospital details  
- `DimPatient` – Patient demographics  
- `DimPhysician` – Physician profiles and specialties  
- `DimPayer` – Insurance payer details  
- `DimDiagnosisCode` – ICD mapping  
- `DimCptCode` – Procedure code details  
- `DimSpeciality` – Specialty classification  
- `DimDate` – Date hierarchy for time-series analysis  

📁 *Schema Reference:*  
![Data Model](assets/er-diagram.png)

---

## 📈 Dashboard Sections

### 🩺 Executive Summary
- High-level overview of healthcare KPIs and trends (2019–2020)  
- Metrics: Total Patients (5,117), Total Expenses (13M), Insurance Revenue (7.5M)

### 🏨 Hospital Analysis
- Evaluates hospital-level performance metrics  
- AR, IPTP, and ARGE ratio trends for financial efficiency  
- Identifies underperforming hospitals for targeted action

### 👩‍⚕️ Patient Analysis
- Demographic insights: age, gender, blood group, and health behavior  
- Lifestyle trends (diet, exercise, tobacco, and alcohol use)  
- Regional analysis across 49 states and 531 cities

### 💰 Payer–Provider Analysis
- Relationship between insurance payers and providers  
- Provider count, FTE distribution, and CPT units  
- Specialty performance metrics across U.S. regions

### 📉 Financial Overview
- Tracks gross vs. adjusted expenses  
- Identifies cost optimization opportunities  
- Monthly and quarterly expenditure trends

---

## ⚙️ Tools & Technologies

| Tool | Purpose |
|------|----------|
| **Microsoft Power BI** | Data modeling, dashboards, and visualizations |
| **Power Query (M)** | Data transformation and cleaning |
| **DAX (Data Analysis Expressions)** | KPI creation and calculations |
| **Excel / CSV** | Data sources |
| **SQL (optional)** | For relational modeling and preprocessing |

---

## 📁 Project Structure

```

Healthcare-Industry-Dynamics-Analysis/
├── analytics/
│   └── US-healthcare-dynamics.pbix
├── assets/
│   ├── er-diagram.png
│   ├── executive_summary.jpg
│   ├── hospital_insights.jpg
│   ├── patient_outcome_analysis.jpg
│   ├── healthcare_provider_metrics.jpg
│   ├── monthly_expenses_trends.jpg
│   ├── project_overview.jpg
│   └── purpose_section.jpg
├── data/
│   ├── FactTable.csv
│   ├── DimHospital.csv
│   ├── DimPatient.csv
│   ├── DimPhysician.csv
│   ├── DimPayer.csv
│   ├── DimSpeciality.csv
│   ├── DimDiagnosisCode.csv
│   ├── DimCptCode.csv
│   ├── DimDate.csv
│   ├── AdjustmentFactor(%).csv
│   ├── BadDepthTable.csv
│   ├── Healthcare_Data.pbix
│   ├── Healthcare_Dataset.xlsb
│   └── DataDictionary.csv
├── notes/
│   ├── Data_Model.pdf
│   ├── DAX.pdf
│   ├── Data_Transformation.pdf
│   ├── Building_Reports.pdf
│   ├── Healthcare_Case_Study.pdf
│   ├── Business_Intelligence.pdf
│   ├── Case.pdf
│   └── Ground_Rules.pdf
├── dashboards.pbix
├── report.pdf
├── schema.png
├── .gitignore
└── README.md

```

---

## 📊 Key Insights

- **83% of total payments** originate from insurance reimbursements.  
- **Midwest and South regions** have the highest provider density.  
- **Expense optimization improved by 45%** through adjusted cost modeling.  
- **Hospital ARGE ratio** stabilized around 31%, improving efficiency.

---

## 💡 Learnings

- Created **optimized Power BI data models** using fact-dimension relationships.  
- Built **interactive dashboards** with bookmarks, slicers, and KPIs.  
- Applied **DAX measures** for advanced calculations and comparisons.  
- Developed **data storytelling** for clear business communication.

---

## 🚀 Future Enhancements

- Integrate **predictive analytics** for patient readmission forecasting.  
- Add **Power BI Service** automation for live dashboards.  
- Implement **data governance & compliance layers** (HIPAA-ready).  

---

## 👨‍💻 Author

**Shivang Kathait**  
📧 [shivangkathait29@gmail.com]  
🔗 [ShivangKathait29](https://github.com/ShivangKathait29)  
📊 *Data Analytics | Business Intelligence | Power BI | Data Visualization*



