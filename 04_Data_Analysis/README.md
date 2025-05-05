# 📊 04_Data_Analysis — Exploring Attrition Drivers

This folder contains the exploratory data analysis (EDA) and visualization work for uncovering drivers of employee attrition using a fictional HR dataset. The insights generated here support the strategic recommendations presented later in the engagement.

---

## 🎯 Purpose & Strategic Context

Employee attrition poses a major risk to operational continuity and talent retention. The objective of this analysis was to:

- Validate initial hypotheses around attrition drivers
- Surface correlations between satisfaction, tenure, and turnover
- Segment findings by department and role to shape tailored strategies

By analyzing real-world-style data, we can translate patterns into meaningful action for leadership, HR, and operations teams.

---

## 🧪 Analysis Conducted

- **Univariate & Bivariate EDA**: Attrition vs. OverTime, Job Satisfaction, Tenure, etc.
- **Correlation Matrix**: Numeric features examined for interdependence
- **Predictive Modeling**: Logistic regression used to classify likelihood of attrition
- **Segmentation**: Attrition rates analyzed by department and job role

---

## 🔍 Key Findings

- 📉 **Sales Representatives** have the highest attrition rate (~40%), followed by Lab Technicians and HR professionals (~24%).
- 🔄 Predictive modeling confirmed **OverTime**, **Years at Company**, and **Job Satisfaction** as top attrition indicators.
- 🧑‍💼 Leadership roles (e.g., Managers, Directors) showed strong retention — potential benchmarks for broader engagement strategy.
- 🧩 Roles with no attrition (e.g., HR Managers) may reflect lower volume or successful internal support structures.

---

## 📁 Included Files

| File | Description |
|------|-------------|
| `exploration.ipynb` | Jupyter Notebook with full analysis, visuals, and strategic summary |
| `attrition_by_role_department.png` | Key chart showing attrition rates by job role and department |
| `mock_data.xlsx` | Fictional HR dataset with engagement and performance fields |
| `exploration_plan.md` | Outlines the structure and business questions for the analysis |
| `data_overview.md` | Summary of dataset contents and business application |

---

## 📌 Strategic Implications

- High-risk roles (Sales, Lab Techs) should be prioritized for retention interventions.
- Predictive modeling enables early identification of at-risk employees.
- Low-attrition segments offer best practices that can be replicated across the org.

---

## 🧠 Next Steps

- Connect key findings to stakeholder personas and transformation plan in Folder 05
- Expand modeling with SHAP values, feature importance, or dashboards (optional)
- Integrate visuals into final story-driven presentation deck

---

> 🔐 **Disclaimer**: All data used here is synthetic and meant solely for demonstration and educational purposes.
