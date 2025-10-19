# 🧳 EasyVisa — Visa Approval Prediction Project

## 📄 Project Overview
**EasyVisa** is a data-driven solution designed for the **Office of Foreign Labor Certification (OFLC)** in the United States to assist in visa application processing.  
With the rapid increase in visa applications each year, manually reviewing and shortlisting candidates for certification has become tedious and time-consuming.  
This project leverages **Machine Learning** to predict visa approval outcomes and identify the key drivers influencing visa certification decisions.

---

## 🎯 Objective
To develop a classification model that can:
- Facilitate the process of visa approvals.
- Identify and recommend applicants who have higher chances of **visa certification**.
- Discover the factors that significantly influence the **case status** (Certified or Denied).

---

## 📊 Dataset Description
**File:** `EasyVisa.csv`

| Column Name | Description |
|--------------|-------------|
| case_id | Unique ID of each visa application |
| continent | Continent of the employee |
| education_of_employee | Education level of the employee |
| has_job_experience | Whether the employee has job experience (Y/N) |
| requires_job_training | Whether the employee requires job training (Y/N) |
| no_of_employees | Number of employees in the employer’s company |
| yr_of_estab | Year the employer’s company was established |
| region_of_employment | Intended region of employment in the US |
| prevailing_wage | Average wage paid for similar occupations in the area |
| unit_of_wage | Unit of wage (Hourly / Weekly / Monthly / Yearly) |
| full_time_position | Whether the position is full-time (Y/N) |
| case_status | Final visa case status — Certified / Denied |

---

## 🧠 Key Analysis Performed
- Data loading, cleaning, and preprocessing.
- Exploratory Data Analysis (EDA) and statistical summaries.
- Categorical encoding and feature transformation.
- Building classification models for visa approval prediction.
- Evaluation using accuracy, precision, recall, F1-score, and ROC-AUC.
- Identification of top predictors influencing visa certification.

---

## 📈 Technologies Used
- **Python** (NumPy, Pandas, Matplotlib, Seaborn, Scikit-learn, Ensemble Learning)
- **Google Colab**
- **HTML Report Generation** (`EasyVisa__Module3_Project.html`)

---

## 📂 Project Structure
- `EasyVisa.csv` — Dataset  
- `EasyVisa__Module3_Project.html` — Project Report

---

## 🔍 Insights Summary
- **Full-time positions** and **higher prevailing wages** showed a strong positive correlation with visa certification.  
- Applicants with **relevant job experience** and **higher education levels** were more likely to be certified.  
- Companies with **more years of establishment** and **larger employee counts** had a higher success rate in certifications.  
- **Unit of wage** and **region of employment** also had noticeable influence on visa outcomes.

---

## 🏁 Conclusion
**The EasyVisa model provides actionable insights to:**
- Help OFLC efficiently shortlist applications with higher chances of certification.
- Highlight key applicant and employer characteristics driving visa approval.
- Support data-backed decisions for optimizing visa processing and reducing manual workload.

