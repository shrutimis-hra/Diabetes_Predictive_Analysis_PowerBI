# Diabetes_Predictive_Analysis_PowerBI
# Healthcare Risk Analytics & Data Governance Dashboard

An executive-ready interactive business intelligence dashboard designed for clinical risk stratification, data profiling, and healthcare data quality management using the Pima Indians Dataset.



## 🛠️ Key Core Tasks Accomplished

### 1. Data Cleaning & Integrity (Power Query ETL)
* **Unmasking Missing Data:** Conducted clinical data profiling and discovered that critical medical indicators like **Insulin (49% missing)** and **SkinThickness (29% missing)** had missing entries hidden as `0` values.
* **Ethical Imputation Handling:** Systematically replaced these impossible zeroes with structured `null` tokens. This prevents artificial skewing of patient averages and safeguards data consistency without dropping critical high-risk patient records.

### 2. Interactive Clinical Analytics
* **Glucose Risk Analysis:** Developed a primary metric analysis showcasing the explicit delta between the average glucose levels of healthy individuals vs. diabetic patients.
* **Demographic Risk Profiling:** Integrated cross-functional visualization combining **Age** trends with **Average Glucose** metrics to visualize risk escalation pathways across different age demographics.
* **Class Distribution Matrix:** Formulated a categorical distribution view showing the dataset's internal balance (~65% normal control cases vs. ~35% high-risk diagnostic instances).

---

## 🛡️ Governance & Patient Privacy Framework

* **De-identification Compliance:**
*
