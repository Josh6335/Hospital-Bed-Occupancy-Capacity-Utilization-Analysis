<div align="center">

# 🏥 Hospital Bed Occupancy & Capacity Utilization Analysis

### A comprehensive analysis of hospital bed utilization and capacity management across ICU and Non-ICU services through data-driven insights

[![Excel](https://img.shields.io/badge/Excel-217346?style=for-the-badge&logo=microsoft-excel&logoColor=white)](https://www.microsoft.com/en-us/microsoft-365/excel)
[![Power BI](https://img.shields.io/badge/Power_BI-F2C811?style=for-the-badge&logo=powerbi&logoColor=black)](https://powerbi.microsoft.com/)


[📊 View Dashboard](#-dashboard-preview) • [📈 Explore Insights](#-key-findings) • [📧 Contact Me](mailto:musedikutemitope@gmail.com)

</div>

---

## 📚 Table of Contents

- [📊 Project Overview](#-project-overview)
- [🎯 Objectives](#-objectives)
- [🛠️ Tools & Technologies](#️-tools--technologies)
- [📁 Dataset Description](#-dataset-description)
- [📂 Project Structure](#-project-structure)
- [🔍 Key Findings](#-key-findings)
- [📸 Dashboard Preview](#-dashboard-preview)
- [💡 How to Use](#-how-to-use)
- [📈 Methodology](#-methodology)
- [🤝 Contributions](#-contributions)
- [📧 Contact](#-contact)

---

## 📊 Project Overview

This project analyzes hospital bed utilization data across Emergency, Surgery, General Medicine, and ICU services to evaluate capacity management effectiveness in a medium-sized hospital. The analysis provides critical insights into occupancy trends, patient flow dynamics, length of stay patterns, and service-level capacity differences to support data-driven decision-making in hospital capacity planning.

<details>
<summary><b>🎯 Click to view Project Highlights</b></summary>

- ✅ Analyzed **13,000+ patient requests** across four major service lines
- ✅ Identified **critical capacity bottlenecks** in Emergency and General Medicine
- ✅ Evaluated **ICU vs Non-ICU performance metrics** and resource allocation
- ✅ Provided **actionable recommendations** for capacity optimization
- ✅ Created **interactive dashboards** for ongoing capacity monitoring

</details>

---

## 🎯 Objectives

<table>
<tr>
<td width="33%" align="center">

### 📊 Capacity Assessment
Evaluate bed occupancy rates and capacity utilization across services

</td>
<td width="33%" align="center">

### 📉 Bottleneck Identification
Identify high-refusal services and demand-capacity imbalances

</td>
<td width="33%" align="center">

### ⏱️ Flow Analysis
Analyze patient length of stay and turnover efficiency

</td>
</tr>
<tr>
<td width="50%" align="center">

### 🏆 Comparative Performance
Compare ICU and Non-ICU operational metrics

</td>
<td width="50%" align="center">

### 💡 Strategic Planning
Provide data-driven recommendations for capacity optimization

</td>
</tr>
</table>

---

## 🛠️ Tools & Technologies

<p align="center">
  <img src="https://img.shields.io/badge/Microsoft_Excel-217346?style=for-the-badge&logo=microsoft-excel&logoColor=white" alt="Excel"/>
  <img src="https://img.shields.io/badge/Power_BI-F2C811?style=for-the-badge&logo=powerbi&logoColor=black" alt="Power BI"/>
  <img src="https://img.shields.io/badge/Data_Analysis-4285F4?style=for-the-badge&logo=google-analytics&logoColor=white" alt="Data Analysis"/>
</p>

| Tool | Purpose |
|------|---------|
| **Microsoft Excel** | Data cleaning, transformation, and preliminary analysis |
| **Power BI** | Interactive dashboard development, data modeling, and advanced visualizations |
| **DAX** | Calculated measures and metrics for performance indicators |

---

## 📁 Dataset Description

A collection of synthetic hospital datasets is designed to simulate real-world operations for a medium-sized hospital, focusing on staffing, patient admissions, and bed allocation among services. The data allows for exploration and analysis of hospital resource distribution, including personnel deployment, patient demand, and service-level performance.

The dataset consists of four CSV files:

- hospital_staff.csv – List of hospital staff
- hospital_patients.csv – Patient records
- hospital_service_weekly.csv – Weekly service-level data
- hospital_staff_schedule.csv – Weekly schedule

### 📌 Data Source
- [Hospital Beds Management](https://www.kaggle.com/datasets/jaderz/hospital-beds-management/data)

---

## 📂 Project Structure

```
Hospital-Bed-Occupancy-Analysis/
│
├── assets/                                  # Dashboard screenshots
│   ├── page1.png
│   ├── page2.png
│   ├── page3.png
│   ├── page4.png
│
├── dataset/                                 # Raw dataset
│   ├── patients.xlsx
│   ├── services_weekly.xlsx
│   ├── staff.xlsx
│   ├── staff_schedule.xlsx   
├── dashboard.pbix                           # Power BI dashboard file            
├── README.md                                # Executive summary report
└── Report.pptx                              # Project documentation
```

---

## 🔍 Key Findings

<div align="center">

### 📊 Overall Performance Snapshot

| Metric | Value | Status |
|--------|-------|--------|
| **Total Patient Requests** | 13,000 | 📈 |
| **Total Admissions** | 6,000 | ✅ |
| **Total Refusals** | 8,000 | 🔴 |
| **Refusal Rate** | 61.5% | 🚨 |
| **Average Bed Occupancy** | 92.5% | ⚠️ |
| **Average Length of Stay** | 7 Days | 📊 |

</div>

### 🚨 Insights

<details open>
<summary><b>Bed Occupancy Rate</b></summary>

- 🚨 Emergency (100%) and General Medicine (97.3%) operate at ceiling every week, driving high refusal rates.
- 📊 ICU (84.4%) and Surgery (88.2%) maintain healthier ranges of bed occupancy rate

</details>

<details>
<summary><b>Demand–Capacity Pressure</b></summary>

- 📍 Emergency (5.2) and General Medicine (1.8) are severely under-resourced, with Emergency identified as the primary bottleneck.
- 📊 ICU ratio: 1.0 (over-resourced relative to demand)
- 🎯 Scatter plot reinforces: Higher occupancy → lower satisfaction.

</details>

> **📌 NOTE:** For the full detailed insight, strategic recommendations, and actionable insights, please refer to the report file  

---

## 📸 Dashboard Preview

<table align="center">
  <tr>
    <td align="center">
      <h3>📊 Cover Page</h3>
      <img src="assets/page1.png" alt="Cover Page" width="400"/>
    </td>
    <td align="center">
      <h3>📈 Overview Dashboard</h3>
      <img src="assets/page2.png" alt="Overview Dashboard" width="400"/>
    </td>
  </tr>
  <tr>
    <td align="center">
      <h3>🏥 ICU vs Non-ICU Comparison</h3>
      <img src="assets/page3.png" alt="ICU Comparison" width="400"/>
    </td>
    <td align="center">
      <h3>🔍 Service-Level Analysis</h3>
      <img src="assets/page4.png" alt="Service Analysis" width="400"/>
    </td>
  </tr>
</table>

---

## 💡 How to Use

### 🚀 Quick Start

1. **📊 Open the Power BI Dashboard**  
   Launch `dashboard.pbix` in Power BI Desktop for interactive analysis

2. **📈 Explore the Data**  
   Check the `dataset/` folder to review raw data

3. **🖼️ View Static Insights**  
   Check the `assets/` folder for high-resolution dashboard screenshots

4. **📄 Read Executive Summary**  
   Review `Report.pptx` for insights and recommendations

---

## 📈 Methodology

<table>
<tr>
<td width="50%">

### 🔧 Technical Approach

1. **Data Preparation**: Cleaning and structuring service-level data for Emergency, Surgery, General Medicine, and ICU
2. **Metric Development**: Calculating bed occupancy rate, average length of stay, refusal rate, and demand-capacity ratios
3. **Trend Analysis**: Examining weekly utilization patterns and service comparisons
4. **Relationship Assessment**: Analyzing correlations between occupancy, length of stay, and patient satisfaction

</td>
<td width="50%">

### 📊 Analytical Framework

- **Capacity Utilization Analysis**: Evaluated occupancy rates against safe thresholds (85%)
- **Demand-Supply Modeling**: Calculated demand-capacity ratios to identify resource gaps
- **Comparative Analytics**: Benchmarked ICU vs Non-ICU performance
- **Patient Flow Assessment**: Analyzed length of stay impact on bed turnover
- **Visualization & Reporting**: Created interactive Power BI dashboards for stakeholder insights

</td>
</tr>
</table>

### 🎯 Key Performance Indicators (KPIs)

- **Bed Occupancy Rate (%)**: Percentage of available beds occupied
- **Average Length of Stay (Days)**: Mean duration patients remain in beds
- **Refusal Rate (%)**: Percentage of admission requests denied
- **Demand-Capacity Ratio**: Ratio of patient requests to bed availability
- **Patient Satisfaction (%)**: Satisfaction scores for admitted patients

---

## 🤝 Contributions

Have suggestions or improvements?  

<p align="center">
  <a href="https://github.com/josh6335/hospital-occupancy-analysis/fork">
    <img src="https://img.shields.io/badge/Fork-Project-blue?style=for-the-badge&logo=github" alt="Fork"/>
  </a>
  <a href="https://github.com/josh6335/hospital-occupancy-analysis/issues">
    <img src="https://img.shields.io/badge/Open-Issue-red?style=for-the-badge&logo=github" alt="Issues"/>
  </a>
  <a href="https://github.com/josh6335/hospital-occupancy-analysis/pulls">
    <img src="https://img.shields.io/badge/Submit-PR-green?style=for-the-badge&logo=github" alt="Pull Request"/>
  </a>
</p>

Feel free to **fork** this repo, **open an issue**, or **submit a pull request**.

---

## 📧 Contact

<div align="center">

### Let's Connect! 🤝

<p>
  <a href="mailto:musedikutemitope@gmail.com">
    <img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="Email"/>
  </a>
  <a href="https://wa.me/2348072240480">
    <img src="https://img.shields.io/badge/WhatsApp-25D366?style=for-the-badge&logo=whatsapp&logoColor=white" alt="WhatsApp"/>
  </a>
  <a href="https://www.linkedin.com/in/joshua-musediku-510945302">
    <img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"/>
  </a>
</p>

**For collaborations, healthcare analytics projects, or data visualization inquiries:**

📩 **Email:** [musedikutemitope@gmail.com](mailto:musedikutemitope@gmail.com)  
💬 **WhatsApp:** [+234 807 224 0480](https://wa.me/2348072240480)  
💼 **LinkedIn:** [Joshua Musediku](https://www.linkedin.com/in/joshua-musediku-510945302)

</div>

---

<div align="center">

### ⭐ If you found this project helpful, please give it a star!

**Made with ❤️ and 📊 by Joshua Musediku**

[![GitHub followers](https://img.shields.io/github/followers/josh6335?style=social)](https://github.com/josh6335)
[![LinkedIn](https://img.shields.io/badge/Follow-LinkedIn-blue?style=social&logo=linkedin)](https://www.linkedin.com/in/joshua-musediku-510945302)

---

**© 2026 Hospital Bed Occupancy & Capacity Utilization Analysis Project. All Rights Reserved.**

</div>
