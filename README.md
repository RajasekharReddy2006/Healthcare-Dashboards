# 🏥 Healthcare Dashboard

This repository contains interactive **Power BI dashboards** built on a healthcare dataset to monitor hospital performance, patient outcomes, risk management, financials, and operational efficiency.  
The dashboards provide actionable insights for administrators, clinicians, and stakeholders to improve care quality and resource allocation.

---

## 📊 Dashboard Pages

### 🏥 Page 1: Executive Overview
- Total number of admitted patients  
- Average Length of Stay (LOS)  
- Total Bill Amount generated  
- Percentage of patients requiring ICU  
- Overall Mortality Rate  
- Average Satisfaction Score  
- Average Emergency Response Time (minutes)  

---

### 🚨 Page 2: Patient Risk & Safety Monitoring
- Patient distribution by Risk Level (Low, Medium, High, Critical)  
- ICU support demand  
- Infection cases reported  
- Readmission within 30 days rate  
- Mortality distribution (Alive vs Deceased)  
- Department with highest Critical risk patients  
- LOS comparison for High vs Critical patients  

---

### 🏥 Page 3: Department & Doctor Performance
- Department with highest patient admissions  
- Doctor handling the most patients  
- Average LOS by Department  
- Department generating the highest Total Bill Amount  
- Doctor with highest patient Satisfaction Score  
- Department with highest Infection cases  

---

### 💰 Page 4: Financial & Insurance Analysis
- Total revenue (Total_Bill_Amount)  
- Average Insurance Coverage %  
- Total Out-of-Pocket Amount paid by patients  
- Admission Type generating the highest revenue  
- Average Hospital Stay Cost per Day by Room Type  
- Impact of LOS on Total Bill Amount  

---

### 🏨 Page 5: Operational Efficiency
- Bed Number utilization across departments  
- Distribution of Room Types (General, Private, ICU)  
- Most common Admission Type (Emergency, Scheduled, Referral)  
- Trend of Admissions over time (Admission_Date)  
- Average Emergency Response Time by Department  

---

## 🛠️ Dataset Attributes Used
- Patient_ID, Patient_Name, Gender, Age  
- Admission_Date, Discharge_Date, Admission_Type  
- Department, Doctor_Name, Diagnosis, Treatment_Type  
- Room_Type, Bed_Number  
- Length_of_Stay, ICU_Required, Infection_Reported, Readmission_Within_30_Days  
- Total_Bill_Amount, Insurance_Coverage_%, Out_of_Pocket_Amount  
- Mortality_Flag, Satisfaction_Score, Emergency_Response_Time_Minutes  
- Hospital_Stay_Cost_Per_Day, Risk_Level  

---

## 📐 Visuals Used
- **Card KPIs** → Admissions, Revenue, Infection Cases  
- **Gauge Charts** → LOS, Readmission Rate, Insurance Coverage %  
- **Pie/Donut Charts** → ICU %, Mortality Distribution, Room Types  
- **Bar/Column Charts** → Risk Levels, Departmental comparisons, LOS by Risk Level  
- **Line Charts** → Admissions trend, Emergency Response Time trend  
- **Scatter Plots** → LOS vs Total Bill Amount  

---

## 🚀 How to Use
1. Clone the repository:
   ```bash
   git clone https://github.com/RajasekharReddy2006/Healthcare-Dashboards.git
Open the Power BI .pbix file in Power BI Desktop.

Connect to the provided dataset (Healthcare_Data.xlsx).

Explore the dashboards and interact with filters for deeper insights.

📌 Purpose
This project is designed to:

Provide real-time hospital performance monitoring.

Help clinicians track patient risk and safety indicators.

Support administrators with financial and operational insights.

Improve patient care quality and resource allocation.

📄 License
This project is licensed under the MIT License – feel free to use, modify, and share.

👨‍💻 Author
Developed by Rajasekhar Reddy  
📍 Hyderabad, India

Code

---

This README will make your repository **professional, easy to navigate, and presentation-ready**.  

Would you like me to also add a **“Screenshots” section** with placeholders so you can
