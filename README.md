# ⚡ Scada_IO_PowerBI

This repository contains a Power BI dashboard developed to analyze the IO Signals (Input/Output points) of *N* number of substations. It offers powerful visual insights into signal sources, feeder configurations, signal classification (Hard/Soft), and data integrity across multiple substations.

---

![image alt](https://github.com/arko1907/Scada_IO_PowerBI/blob/86c80828d7e141e969c3673030aaa74a4962b387/SCADADashboard.jpg)


## 🎯 Problem Statement

Auditing IO lists across multiple substations is typically manual, time-consuming, and error-prone. Stakeholders often lack a consolidated view of IO signal distribution, source quality, feeder types, and hardware/software split.

This dashboard aims to **automate the auditing process**, provide **standardized analysis**, and support **informed decision-making** on signal configurations and data consistency.

---

## ✅ AIMS Grid

| Aspect           | Description |
|------------------|-------------|
| **Audience**     | SCADA engineers, commissioning teams, data auditors, system integrators |
| **Intent**       | Provide an interactive, consolidated view of IO signals across multiple substations |
| **Means**        | Power BI dashboard with dynamic filtering, grouping, and categorization |
| **Scope**        | N number of substations with `.xlsx` IO lists in standardized or semi-standardized formats |

---

## 📊 Key Insights Provided by the Dashboard

- 🔢 **Total Signal Count by Substation** – Understand the volume of IO points per site.
- 🧭 **Feeder Types by Voltage Level** – Get a categorized count of feeders per voltage level (e.g., ACDB, Bus Coupler, Transformer).
- 🧠 **Signal Type Breakdown** – Classify signals by types like AI, DI, DO, SPC, DPC, HDR, etc.
- ⚙️ **Hard vs Soft Signal Classification** – Easily identify how many signals are configured as hardwired vs soft.
- 📥 **Source-wise Signal Distribution** – Identify which IO sources (MFT, IED, Transducer, RTU, etc.) contribute most to signal population.
- 🔍 **Substation-level Filtering** – Use slicers to isolate insights for one or more substations.
- 🧹 **Data Quality Metrics** – Visuals indicate missing or blank values that may need review.

---

## 📦 Repository Structure

```
├── Total_raw/
│   ├── SS_1.xlsx
│   ├── SS_10.xlsx
│   └── ... more substations
├── SS_IO_Check_p.pbix         # Power BI dashboard file
├── README.md                  # Project documentation
```

---

## 💡 Value for Stakeholders

| Stakeholder         | Benefit |
|---------------------|---------|
| **SCADA Engineers** | Visual validation of IO configuration integrity |
| **QA/Audit Teams**  | Instant snapshot of missing values or unusual distributions |
| **Commissioning**   | Confidence in signal readiness per voltage/feeder |
| **System Designers**| Support for load estimation, architecture decisions |

---

## 🧹 Challenges Faced During Data Cleaning & Dashboard Design

### 1. Inconsistent File Structures
- Excel files across substations had different formats, headers, and layouts.

### 2. Classification Challenges
- Soft/Hard signal categorization lacked consistency, requiring normalization.

### 3. Scalability and Maintenance
- Built with flexibility so new substations can be added by placing files in the folder.



---

## 📌 How to Use

1. Clone or download the repository.
2. Open `SS_IO_Check_p.pbix` in Power BI Desktop.
3. Place all `.xlsx` substation files in the `Total_raw` directory.
4. Refresh the dashboard to update visuals with the latest data.

---

## 📷 Screenshot Preview

- 🔢[Dashboard Overview](https://github.com/arko1907/Scada_IO_PowerBI/blob/main/SCADA_Dashboard.jpg)
- ![Dashboard Preview](images/dashboard.jpeg)
- <img src="arko1907/Scada_IO_PowerBI/blob/main/SCADA_Dashboard.jpg" alt="Dashboard Preview" width="600"/>

---

## 🔧 Requirements

- Power BI Desktop (latest version recommended)
- Excel files in compatible `.xlsx` format

---

## 📬 Contributions

Feel free to raise an issue or pull request if you'd like to contribute improvements.

---

© 2025 — Developed by [arko1907](https://github.com/arko1907)
