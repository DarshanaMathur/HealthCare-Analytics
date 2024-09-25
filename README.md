# 🏥 Healthcare Analytics Dashboard

### 📊 Comprehensive Dashboard for Encounter, Payer, and Cost Analysis

---

## 📁 Problem Statement

A healthcare provider is struggling to understand health trends, payer mix, and cost patterns within their patient population. They need a **dashboard** to provide insights into:
- **Encounter types**
- **Patient demographics**
- **Payer performance**
- **Cost analysis**

This dashboard helps optimize resource allocation, improve patient care, and manage financial performance.

---

## 🧠 Executive Summary

The **Healthcare Analytics Dashboard** offers a detailed view into the healthcare provider’s operations. It highlights critical insights into encounter types, patient demographics, and payer contributions, helping in:
- **Improved decision-making**
- **Better financial management**
- **Enhanced patient care strategies**

---

## 🔎 Key Insights and Recommendations

### 🔹 Encounters Overview:
- **Average Encounter Age**: 52 years
- **Most Common Encounter Types**: 
  - Ambulatory (20,311)
  - Emergency (774)
  - Inpatient (200)
- **Ethnicity Distribution**:
  - Hispanic: 2,370 encounters
  - Non-Hispanic: 19,210 encounters
- **Vaccination Stats**:
  - 2,370 individuals have received both COVID-19 and Flu shots

### 🔹 Payer's Overview:
- **Largest Payer Category**: PRIVATE (42.84%)
- **Payers with Most Encounters**: 
  - United Healthcare (21.58K encounters)
  - Aetna (52.35%)
- **Cost Analysis**:
  - United Healthcare has the highest total claim cost but a lower average claim cost per encounter than Aetna or Anthem.

### 🔹 Actionable Recommendations:
1. **Optimize Resource Allocation**: Focus on ambulatory and emergency encounters to reduce wait times.
2. **Preventive Care**: Promote preventive services to lower emergency encounters.
3. **Contract Negotiation**: Negotiate contracts with high-volume payers like United Healthcare for better reimbursement rates.
4. **Cost Benchmarking**: Compare average claim cost with industry standards to reduce expenses.
5. **Cultural Competency**: Enhance language services and community outreach to better serve diverse populations.

---

## 🚀 Technologies Used

- **Python**: Scripted to download data using the **Kaggle API**.
- **SQL**: Extracted insights and performed data modeling for further dashboard development.
- **Tableau**: Used for visualization and dashboard creation.

---

## 📊 Dashboard Structure

### 🟦 Encounters Overview:
Analyzes the distribution of encounter types (e.g., ambulatory, emergency), patient age, and ethnicity. It helps healthcare providers better allocate resources and tailor their service offerings based on patient demographics and needs.

### 🟩 Payer's Overview:
Evaluates the payer mix and its influence on revenue. It also compares the average claim cost per payer and identifies opportunities for cost negotiation and management.

### 🟨 Insights and Recommendations:
Provides actionable insights and strategic recommendations for resource optimization, payer mix improvement, and cost control.

### 🟧 Conclusion:
Emphasizes how the dashboard aids healthcare organizations in addressing health trends, improving care, and managing financial performance effectively.

---

## 📖 Data Dictionary

| **Field**               | **Description**                                         |
|-------------------------|---------------------------------------------------------|
| `encounter_id`           | Unique identifier for each encounter                    |
| `start`                  | Start timestamp of the encounter                        |
| `stop`                   | End timestamp of the encounter                          |
| `encounterclass`         | Class of the encounter (e.g., ambulatory, hospice)      |
| `enc_type`               | Type of encounter (e.g., Hospital Encounter)            |
| `base_encounter_cost`    | Base cost of the encounter                              |
| `total_claim_cost`       | Total claim cost for the encounter                      |
| `organization`           | Unique identifier for the organization                  |
| `enc_reason`             | Reason for the encounter                                |
| `payer`                  | Payer for the encounter (e.g., Medicare)                |
| `payer_category`         | Category of the payer (e.g., Government)                |
| `patient_id`             | Unique identifier for the patient                       |
| `ethnicity`              | Ethnicity of the patient                                |
| `race`                   | Race of the patient                                     |
| `flu_2022`               | Flu vaccination status in 2022                          |
| `covid`                  | COVID vaccination status                                |
| `org_name`               | Name of the organization                                |
| `org_zip`                | Zip code of the organization                            |
| `org_city`               | City of the organization                                |
| `org_state`              | State of the organization                               |

---

## 📈 Key Findings

1. **High Ambulatory Encounters**: A significant number of encounters (20,311) are ambulatory. This points to opportunities for optimizing outpatient services.
2. **Private Payers Dominate**: Private payers cover 42.84% of all encounters, indicating a potential area for improving contract terms.
3. **United Healthcare Costs**: Despite the highest total claim cost, United Healthcare has lower average claim costs per encounter compared to Aetna and Anthem.

---

## 📌 Recommendations

- **Invest in Ambulatory Resources**: Address the high volume of ambulatory encounters by enhancing resources in outpatient care.
- **Preventive Services**: Focus on reducing emergency encounters by increasing awareness of preventive healthcare.
- **Payer Negotiations**: Reassess contracts with private payers to secure better rates.
- **Cost Control**: Implement cost-saving initiatives like optimizing medication management and reducing waste.
- **Cultural Outreach**: Strengthen cultural competency and provide language services to improve patient outcomes for diverse populations.

---

## 🏆 Conclusion

The **Healthcare Analytics Dashboard** offers critical insights to improve patient care, optimize resource utilization, and manage financial performance. By leveraging this dashboard, healthcare organizations can take actionable steps to enhance care delivery, reduce costs, and ensure better financial management.

---

## 👩‍💻 Author

**Darshana Mathur**  
[LinkedIn](https://www.linkedin.com/in/darshanamathur4) | [Tableau Public Profile](https://public.tableau.com/app/profile/darshana.mathur/vizzes)

