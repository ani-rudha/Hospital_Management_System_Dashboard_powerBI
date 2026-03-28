# 🏥 Hospital Operations, Patient Flow & Financial Performance Intelligence Dashboard (Power BI)

This project presents an end-to-end **Healthcare Business Intelligence Dashboard** built using Power BI to analyze hospital operations, patient flow, resource utilization, and financial performance.

The dashboard integrates **patient analytics, operational efficiency monitoring, department performance tracking, and billing insights** to simulate a real-world hospital analytics environment focused on healthcare operations and financial sustainability.

---

## ✴️ Project Overview

The objective of this project was to:

- Design a clean **star-schema data model**
- Implement **advanced DAX measures**
- Build **executive-ready KPI dashboards**
- Monitor **bed occupancy and patient flow trends**
- Analyze **department and doctor performance**
- Deliver **actionable insights for hospital operations and financial management**

---

## 🎯 Business Objectives

- Measure overall hospital patient and revenue performance.
- Monitor hospital operational efficiency and resource utilization.
- Track patient admissions and bed occupancy trends.
- Identify high-demand departments and service usage patterns.
- Analyze patient demographics and geographic distribution.
- Evaluate hospital billing and payment performance.
- Provide insights to improve hospital planning and service delivery.

---

## 📂 Dataset Description

The dataset consists of the following tables:

| Table | Description |
|------|------------|
| `Admissions` | Patient admission records including admission type, department, doctor and bed allocation |
| `Patients` | Patient demographic details including age, gender and city |
| `Doctors` | Doctor information and department assignments |
| `Departments` | Hospital department information |
| `Billing` | Billing transactions including bill amount and payment status |
| `Date` | Calendar table used for time intelligence |
| `MyMeasures` | Dedicated table to store all DAX measures |

The dataset simulates a **real-world hospital data warehouse structure**.

---

## 🧱 Data Model Design

The model follows a **star schema structure**:

- `Admissions` acts as the primary **hospital operations fact table**
- `Billing` tracks **financial transactions and revenue**
- `Patients` provides **demographic segmentation**
- `Doctors` enables **doctor performance analysis**
- `Departments` supports **department-level performance tracking**
- `Date` supports **time intelligence calculations**

Relationships are built using **patient_id, doctor_id, department_id and date keys** with one-to-many cardinality.

This structure ensures **proper filter propagation and accurate KPI calculations**.

---

## 🧮 Key DAX Measures

### Core Hospital KPIs

- Total Patients
- Total Revenue
- Bed Occupancy Rate
- Total Admissions
- Total Doctors
- Active Patients

### Operational Efficiency Metrics

- Average Length of Stay
- Admissions by Department
- Admissions by Doctor
- Department Performance
- Bed Occupancy Trend
- Admission Type Distribution (OPD, IPD, Emergency)

### Patient Demographics Analysis

- Patient Age Distribution
- Gender Distribution
- City-wise Patient Count
- Patient Growth Trend
- Patient Segmentation Analysis

### Financial Performance Metrics

- Total Bills
- Average Bill Value
- Revenue by Department
- Average Treatment Cost
- Payment Status Distribution
- Co-payment Distribution

All measures were implemented using **proper filter context handling** to ensure KPI accuracy across all dashboard filters.

---

## 📈 Dashboard Structure

### 1️⃣ Executive Overview — Hospital Performance

- Total Patients
- Total Revenue
- Bed Occupancy Rate
- Monthly Revenue Trend
- Bed Occupancy Trend
- Department Performance
- Revenue by Admission Type

Purpose: Provide a **high-level executive overview of hospital operations**, including patient demand, revenue trends, and resource utilization.

---

### 2️⃣ Operational Analysis — Hospital Efficiency

- Total Doctors
- Average Length of Stay
- Total Admissions
- Admissions by Doctor
- Admissions by Department
- Average Length of Stay by Department
- Admission Type Distribution (OPD, IPD, Emergency)

Purpose: Analyze **hospital operations, department performance, and doctor workload distribution**.

---

### 3️⃣ Patient Analysis — Demographics & Demand

- Total Patients
- Age Distribution
- Gender Split
- City-wise Patients (Map View)

Purpose: Understand **patient demographics and geographic distribution** to support healthcare planning and service allocation.

---

### 4️⃣ Financial Analysis — Revenue & Billing Intelligence

- Average Bill Value
- Total Bills
- Revenue by Department
- Average Treatment Cost by Department
- Payment Status Distribution
- Co-payment Distribution

Purpose: Evaluate **hospital financial performance, billing trends, and payment behavior**.

---

## 📝 Overall Dashboard Objective

To provide a **complete 360° view of hospital operations** by combining:

- Patient Flow Analysis
- Operational Efficiency Monitoring
- Resource Utilization Tracking
- Financial Performance Insights

This enables hospitals to **improve service delivery, optimize capacity planning, and maintain financial efficiency**.

---

## 🎨 Advance UX Features

- Page navigation buttons for smooth dashboard navigation
- Dynamic KPI cards with monthly comparison
- Interactive filtering across multiple pages
- Map-based geographic patient analysis
- Custom `MyMeasures` table for clean DAX management
- Consistent KPI color themes for performance indicators

The dashboard balances **analytical depth with professional presentation design**.

---

## 🔍 Key Business Insights

- Bed occupancy trends indicate hospital capacity utilization patterns.
- Certain departments handle significantly higher patient volumes.
- Average length of stay varies across departments.
- Emergency admissions contribute significantly to patient demand.
- Revenue performance closely follows patient admission trends.
- Payment status distribution highlights billing efficiency.

---

## 💼 Business Recommendations

- Monitor bed occupancy levels to optimize hospital capacity planning.
- Allocate additional resources to high-demand departments.
- Reduce patient length of stay through process optimization.
- Improve billing efficiency for pending payment cases.
- Track patient demographics to support future healthcare planning.

---

## 🛠 Tools Used

- Power BI
- Data Modeling (Star Schema Logic)
- Advanced DAX Measures
- Power Query (Data Cleaning & Transformation)
- Healthcare Operations Analytics Techniques
- Business Intelligence Visualization Design

---

## 🚀 Portfolio Value

This project demonstrates:

- End-to-end BI dashboard development
- Strong data modeling fundamentals
- Advanced DAX implementation
- Healthcare operations analytics
- KPI dashboard design
- Business storytelling through dashboards

Suitable for roles in:

- Data Analyst
- Business Intelligence Analyst
- Healthcare Data Analyst
- Operations Analyst

It reflects the ability to **transform hospital operational data into actionable business insights**.

---

> Note: *For any questions or collaboration opportunities, feel free to reach out!*
