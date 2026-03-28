# 🏥 Hospital Operations & Financial Performance Intelligence Dashboard (Power BI)

---

# ✴️ Project Overview

This project presents an end-to-end **Healthcare Business Intelligence Dashboard** built using **Power BI** to analyze hospital operations, patient demographics, bed utilization, and financial performance.

The objective was to design a structured relational data model, implement robust DAX measures, and build executive-level analytics that connect patient flow, operational efficiency, and revenue performance.

The dashboard integrates **patient management analytics, hospital operational monitoring, resource utilization tracking, and financial performance insights** to simulate a real-world healthcare analytics environment.

It provides a **360° operational and financial view** of hospital performance, enabling decision-makers to monitor patient demand, optimize bed utilization, and track revenue drivers.

---

# 🎯 Business Objectives

- Measure overall hospital patient and revenue performance  
- Monitor hospital operational efficiency and resource utilization  
- Track bed occupancy and patient flow trends  
- Identify department-level performance and service demand  
- Analyze patient demographics and geographic distribution  
- Evaluate hospital billing and payment performance  
- Provide actionable insights for hospital management and planning  

---

# 📂 Dataset Description

The dataset consists of structured hospital system tables representing patient admissions, hospital departments, doctors, billing records, and patient demographics.

| Table | Description |
|------|-------------|
| `Admissions` | Patient admission records including admission type, department, doctor, and bed allocation |
| `Patients` | Patient demographic information including age, gender, and city |
| `Doctors` | Doctor details and department assignments |
| `Departments` | Hospital department information |
| `Billing` | Billing transactions including total bill amount and payment status |
| `Date` | Calendar table used for time intelligence |
| `MyMeasures` | Dedicated table to store all DAX measures |

The dataset simulates a **real-world hospital data warehouse environment**.

---

# 🧱 Data Model Design

The model follows a clean **star-schema structure** for optimal performance and analytical flexibility.



---

## Model Characteristics

- One-to-Many relationships maintained  
- Single-direction filtering applied across fact tables  
- Dimension tables provide consistent filtering context  
- No ambiguous relationships or circular dependencies  
- Dedicated **MyMeasures table** used for centralized DAX management  

---

# 🧮 Key DAX Measures Implemented

## 1️⃣ Core Hospital KPIs

- Total Patients  
- Total Revenue  
- Bed Occupancy Rate  
- Active Patients  
- Total Admissions  
- Total Doctors  

## 2️⃣ Operational Efficiency Metrics

- Average Length of Stay  
- Admissions by Department  
- Admissions by Doctor  
- Department Performance  
- Bed Occupancy Trend  
- Admission Type Distribution (OPD, IPD, Emergency)  

## 3️⃣ Patient Demographics Analysis

- Patient Age Distribution  
- Gender Distribution  
- City-wise Patient Count  
- Patient Growth Trend  
- Total Patients by Demographic Segment  

## 4️⃣ Financial Performance Metrics

- Total Bills  
- Average Bill Value  
- Revenue by Department  
- Average Treatment Cost  
- Payment Status Distribution  
- Co-payment Distribution  

All measures were implemented using proper **filter context handling**, **time intelligence functions**, and **aggregation logic** to ensure KPI accuracy across slicers and filters.

---

# 📈 Dashboard Pages

## 1️⃣ Executive Overview — Hospital Performance

### KPIs

- Total Patients  
- Total Revenue  
- Bed Occupancy Rate  

### Visuals

- Monthly Revenue Trend  
- Bed Occupancy Trend  
- Department Performance  
- Revenue by Admission Type  

`Purpose : Provide a high-level executive overview of hospital operations, including patient demand, revenue growth, and resource utilization.`

## 2️⃣ Operational Analysis — Hospital Efficiency

### KPIs

- Total Doctors  
- Average Length of Stay  
- Total Admissions  

### Visuals

- Admissions by Doctor  
- Admissions by Department  
- Average Length of Stay by Department  
- Admission Type Distribution  

### Interactive Feature

Button-based navigation to display a detailed operational table showing:

- Doctor  
- Department  
- Admission Count  
- Revenue  
- Operational Efficiency  

`Purpose : Evaluate hospital operational efficiency, doctor workload distribution, and department-level performance.`

## 3️⃣ Patient Analysis — Demographics & Demand

### KPIs

- Total Patients  

### Visuals

- Age Distribution (Line & Clustered Column Chart)  
- Gender Split (Pie Chart)  
- City-wise Patients (Map View)  

`Purpose : Analyze patient demographics and geographic distribution to support hospital planning and service allocation.`

## 4️⃣ Financial Analysis — Revenue & Billing Intelligence

### KPIs

- Average Bill Value  
- Total Bills  

### Visuals

- Revenue by Department  
- Average Treatment Cost by Department  
- Payment Status Distribution  
- Co-payment Distribution  

### Purpose

Monitor hospital financial performance, billing efficiency, and payment behavior.

---

# 📝 Overall Dashboard Objective

To provide a complete **hospital intelligence framework** by integrating:

- Patient demand analysis  
- Operational efficiency monitoring  
- Resource utilization tracking  
- Financial performance measurement  

This enables hospital administrators to improve service delivery, optimize resource allocation, and maintain financial sustainability.

---

# 🎨 Advanced UX Features

- Interactive page navigation buttons  
- Dynamic KPI cards with monthly comparison  
- Conditional color indicators for performance trends  
- Map-based geographic patient analysis  
- Centralized MyMeasures table for DAX management  
- Consistent visual theme and layout across pages  

The dashboard balances **analytical depth**, **performance**, and **professional user experience design**.

---

# 🔍 Key Business Insights

- Bed occupancy trends reveal hospital capacity utilization patterns  
- Certain departments receive significantly higher patient demand  
- Average length of stay varies across departments  
- Emergency admissions contribute a major share of patient volume  
- Revenue performance is closely linked to patient admission trends  
- Payment status distribution highlights billing collection efficiency  

Note: Dataset is synthetic; therefore some patterns may appear smoother than real-world hospital data.

---

# 💼 Business Recommendations

- Monitor bed occupancy levels to optimize hospital capacity planning  
- Allocate additional resources to high-demand departments  
- Reduce patient length of stay through process optimization  
- Improve billing efficiency for pending payment cases  
- Track patient demographics to plan future healthcare services  

---

# ⚒️ Tools Used

- Power BI  
- Data Modeling (Star Schema Design)  
- Advanced DAX Measures  
- Power Query (Data Transformation)  
- Healthcare Operations Analytics  
- Business Intelligence Visualization Design  

---

# 🚀 Portfolio Value

This project demonstrates:

- End-to-end BI dashboard development  
- Healthcare operations analytics  
- Advanced DAX implementation  
- Interactive dashboard design  
- Data modeling best practices  
- Business storytelling through dashboards  

---

# 🧑🏻 Author

**Anirudha Das**  
Aspiring Data Analyst / Business Intelligence Professional  
📍 West Bengal, India
