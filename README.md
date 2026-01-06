# Hospital-Data-Analysis-Management_Dashboard-Power-BI
This Hospital Analytics Dashboard is an end-to-end Power BI project designed to provide 360-degree visibility into hospital operations, patient management, doctor performance, resource utilization, and financial performance. The project demonstrates strong skills in data modeling, DAX, Power Query transformations, KPI design, &amp; storytelling data.

# Hospital Analytics Dashboard – Power BI Project


## 1. Project Overview

This **Hospital Analytics Dashboard** is an end-to-end Power BI project designed to provide **360-degree visibility** into hospital operations, patient management, doctor performance, resource utilization, and financial performance.

The dashboard is structured into **multiple role-based and function-based pages**:

* Home Page- [Home Page.png](https://github.com/kumar98rishav-oss/Hospital-Data-Analysis-Management_Dashboard-Power-BI/blob/20c236acf749b1bbde856e507d207cd1d6234998/Home%20Page.png)
* Overview Dashboard- [Overview Page.png](https://github.com/kumar98rishav-oss/Hospital-Data-Analysis-Management_Dashboard-Power-BI/blob/20c236acf749b1bbde856e507d207cd1d6234998/Overview%20Page.png)
* Patient Dashboard- [Patient Page.png](https://github.com/kumar98rishav-oss/Hospital-Data-Analysis-Management_Dashboard-Power-BI/blob/ccf8ce7ac8f75f2680054938fdb36d437419b0ec/Patient%20Page.png)
* Doctor Dashboard- [Doctor Page.png](https://github.com/kumar98rishav-oss/Hospital-Data-Analysis-Management_Dashboard-Power-BI/blob/20c236acf749b1bbde856e507d207cd1d6234998/Doctor%20Page.png)
* Hospital Dashboard- [Hospital Page.png](https://github.com/kumar98rishav-oss/Hospital-Data-Analysis-Management_Dashboard-Power-BI/blob/20c236acf749b1bbde856e507d207cd1d6234998/Hospital%20Page.png)
* Finance Dashboard- [Finance Page.png](https://github.com/kumar98rishav-oss/Hospital-Data-Analysis-Management_Dashboard-Power-BI/blob/20c236acf749b1bbde856e507d207cd1d6234998/Finance%20Page.png)

The project demonstrates strong skills in **data modeling, DAX measures, Power Query transformations, KPI design, storytelling with data, and UI/UX best practices**.

---

## 2. Business Objective

The primary goal of this project is to help **hospital management and decision-makers**:

* Monitor operational efficiency
* Track patient flow and outcomes
* Evaluate doctor performance and revenue contribution
* Optimize bed, room, and medicine stock utilization
* Analyze hospital financial health

---

## 3. Key KPIs Defined

### 3.1 Overall Hospital KPIs

* **Total Patients** – Total number of patients admitted
* **Total Doctors** – Active doctors in the hospital
* **Total Staff** – Supporting medical and non-medical staff
* **Total Beds** – Hospital bed capacity
* **Occupied Beds vs Available Beds (%)**
* **Patient Discharge Rate (%)**
* **Average Patient Rating**

---

### 3.2 Patient KPIs

* **Patient Count by Age Group** (18–30, 31–45, 46–60, 60+)
* **Admission Status** (Admitted / Discharged)
* **Average Length of Stay (Days)**
* **Diagnosis-wise Patient Distribution**
* **Total Bill Amount per Patient**
* **Medicine Quantity Consumed**
* **Patient Satisfaction Rating**

---

### 3.3 Doctor KPIs

* **Total Appointments**
* **Patient Spend per Doctor**
* **Commission Rate (%)**
* **Commission Earned**
* **Doctor-wise Revenue Contribution**
* **Specialization-wise Performance**
* **Doctor Availability Status**

---

### 3.4 Hospital Operations KPIs

* **Room Status** (Available vs Occupied)
* **ICU / General / Private Room Utilization**
* **Surgery Count**
* **Department-wise Patient Load**
* **Appointment Trends**

---

### 3.5 Finance KPIs

* **Total Billing Amount**
* **Average Doctor Salary**
* **Average Staff Salary**
* **Medicine Sales Amount**
* **Test Revenue**
* **Discount Impact on Revenue**
* **Monthly Medicine Sales Trend**

---

## 4. Dashboard Page-wise Analysis

### 4.1 Overview Dashboard

**Purpose:** High-level snapshot for top management

**Insights Available:**

* Overall hospital performance at a glance
* Patient admission and discharge trends by month
* Bed availability vs occupancy
* Revenue distribution by charge type (Surgery, Room, Test, Doctor, Medicine)
* Appointment pipeline

**Key Insight Example:**

* Surgery contributes the **highest revenue share**, followed by room charges.
* Discharge rate around **70%**, indicating efficient patient flow.

---

### 4.2 Patient Dashboard

**Purpose:** Deep dive into individual patient journey

**Insights Available:**

* Patient demographic analysis (age, gender, blood group)
* Diagnosis and assigned doctor
* Length of stay and room type
* Medicine usage by category
* Total bill and medicine quantity

**Key Insight Example:**

* Patients aged **31–45 and 46–60** form the majority of admissions.
* Medicine consumption is highest for **critical treatments**, not general medication.

---

### 4.3 Doctor Dashboard

**Purpose:** Performance and revenue tracking of doctors

**Insights Available:**

* Doctor profile (specialization, department)
* Appointments handled
* Patient spend per doctor
* Commission calculation using dynamic slicers
* Doctor-wise revenue table

**Key Insight Example:**

* Cardiologists and surgeons generate **higher patient spend**.
* Commission model allows management to simulate incentive changes.

---

### 4.4 Hospital Dashboard

**Purpose:** Operational efficiency monitoring

**Insights Available:**

* Room utilization by category (ICU, General, Private)
* Surgery schedules
* Department workload
* Age-wise patient distribution

**Key Insight Example:**

* ICU occupancy is high compared to availability → potential expansion area.

---

### 4.5 Finance Dashboard

**Purpose:** Financial health and cost control

**Insights Available:**

* Monthly medicine sales trend
* Stock vs sales comparison
* Revenue by billing type
* Salary vs revenue comparison

**Key Insight Example:**

* Certain medicines show **high stock but low sales**, indicating inventory optimization opportunity.

---

## 5. Tools & Techniques Used

### Data Source & Backend (MySQL)

* Designed and queried data from **MySQL database**
* Used **SQL joins (INNER, LEFT)** to combine multiple tables (Patients, Doctors, Appointments, Billing, Medicine, Rooms, Staff)
* Applied filtering, aggregation, and data validation at the database level before import
* Ensured relational integrity across fact and dimension tables

### Data Modeling & ETL (Power BI)

* Imported structured data from MySQL into Power BI
* Performed extensive **data cleaning and transformation in Power Query**, including:

  * Handling nulls and inconsistencies
  * Data type standardization
  * Column splitting/merging
  * Derived columns for analysis
* Implemented a **Snowflake Schema** for optimized data modeling
* Created **bridge tables** to resolve many-to-many relationships (e.g., Doctor–Patient, Patient–Medicine)

### Power BI Skills Demonstrated

* SQL-based data extraction from MySQL
* Snowflake schema data modeling
* Bridge tables for complex relationships
* Data Modeling (Fact & Dimension tables)
* Power Query (ETL, cleaning, transformations)
* DAX Measures (KPIs, % calculations, running totals)
* Dynamic slicers & filters
* Custom visuals & tooltips
* Interactive navigation using buttons
* Professional UI/UX layout

### Power BI Skills Demonstrated

* Data Modeling (Star Schema)
* Power Query (ETL, cleaning, transformations)
* DAX Measures (KPIs, % calculations, running totals)
* Dynamic slicers & filters
* Custom visuals & tooltips
* Interactive navigation using buttons
* Professional UI/UX layout

---

## 6. Business Insights Summary

* Surgery and room charges are the **primary revenue drivers**.
* Middle-aged patients dominate hospital admissions.
* Doctor performance varies significantly by specialization.
* Medicine inventory management can be optimized.
* Bed occupancy trends help plan capacity expansion.

---

## 7. Value to Stakeholders

* **Management:** Strategic planning & profitability analysis
* **Doctors:** Performance and incentive tracking
* **Operations Team:** Bed, room, and staff optimization
* **Finance Team:** Revenue leakage and cost control

---

## 8. Resume / Portfolio Description (Short Version)

> Designed an interactive Hospital Analytics Dashboard in Power BI covering patient management, doctor performance, hospital operations, and financial insights. Implemented advanced DAX KPIs, dynamic slicers, and business-focused visuals to support data-driven healthcare decision-making.

---

## 9. Possible Future Enhancements

* Predictive patient admission forecasting
* Readmission risk analysis
* Real-time data integration
* Advanced financial profitability modeling
* Machine learning-based patient outcome prediction

---

**This project reflects real-world healthcare analytics use cases and demonstrates strong analytical and visualization capabilities suitable for Data Analyst and Power BI roles.**
