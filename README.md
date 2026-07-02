# 🏥 Hospital Emergency Room Dashboard

An interactive Power BI dashboard designed to monitor and analyze the daily operations of a hospital's Emergency Room (ER). The dashboard provides a monthly view of key performance indicators, patient demographics, admission trends, and department referrals to support data-driven decision-making for hospital management

---

## 📊 Overview

The **Hospital Emergency Room Dashboard** consolidates critical ER metrics into a single, easy-to-read view. It allows stakeholders to filter data by **Month** and **Year**, making it simple to track performance trends over time and identify areas for operational improvement.

---

## ✨ Key Features

### 🔑 Key Performance Indicators (KPIs)
- **No. of Patients** – Total patients visiting the ER
- **Avg Wait Time** – Average time (in minutes) patients wait before being seen
- **Patient Satisfaction Score** – Average satisfaction rating
- **No. of Patients Referred** – Total patients referred to other departments

### 📈 Visual Insights
- **Patient Admission Status** – Breakdown of Admitted vs. Not Admitted patients
- **% of Patients Seen Within 30 Minutes** – Donut chart comparing patients seen within target vs. target missed
- **No. of Patients by Age Group** – Distribution of patients across age brackets
- **No. of Patients by Gender** – Male, Female, and Not Conformed breakdown
- **No. of Patients by Department Referral** – Referrals to General Practice, Orthopedics, Physiotherapy, Cardiology, Gastroenterology, Neurology, and Renal departments
- **No. of Patients by Patient Race** – Distribution across White, African American, Asian, Native American, Pacific Islander, and other groups
- **No. of Patients by Day and Hour** – Heatmap-style matrix showing patient inflow across days of the week and time slots (helps identify peak hours)

### 🎛️ Interactivity
- **Month Name** and **Year** slicers to filter the entire dashboard dynamically
- Trend sparklines on each KPI card for at-a-glance historical context

---

## 🛠️ Tools & Technologies

- **Power BI** – Dashboard design, DAX calculations, and data visualization
- **Excel / SQL** *(data source — update as applicable)* – Source data for ER records

> ⚠️ Update this section with the actual data source and tools you used (e.g., Excel, SQL Server, CSV export) before publishing.

---

## 📂 Repository Structure

```
├── Hospital_ER_Dashboard.pbix     # Power BI dashboard file
├── data/                          # Source dataset(s)
├── images/                        # Dashboard screenshots
└── README.md                      # Project documentation
```

---

## 🚀 How to Use

1. Clone this repository:
   ```bash
   git clone https://github.com/Kamra-Piyush/hospital-er-dashboard.git
   ```
2. Open the `.pbix` file in **Power BI Desktop**.
3. Use the **Month Name** and **Year** filters at the top-right to explore different time periods.
4. Hover over charts and cards for detailed tooltips.

---

## 📌 Insights You Can Derive

- Peak hours and days of ER congestion (via the Day/Hour heatmap)
- Whether wait-time targets (30 minutes) are consistently being met
- Age, gender, and racial demographics of ER patients
- Most common department referrals from the ER
- Trends in patient satisfaction and admission rates over time

---

## 👤 Author

Piyush Kamra  
📧 piyushkamra20@gmail.com

##
This project is open-source and available under the [MIT License](LICENSE).
