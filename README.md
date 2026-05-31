<div align="center">

<img src="https://img.shields.io/badge/Power%20BI-F2C811?style=for-the-badge&logo=powerbi&logoColor=black" />
<img src="https://img.shields.io/badge/HR%20Analytics-DC143C?style=for-the-badge&logo=databricks&logoColor=white" />
<img src="https://img.shields.io/badge/Data%20Insights-1470AF?style=for-the-badge&logo=microsoftexcel&logoColor=white" />
<img src="https://img.shields.io/badge/Status-Active-brightgreen?style=for-the-badge" />

<br/><br/>

# 🏢 HR Analytics Dashboard — Full Insight

### *A comprehensive Power BI report delivering workforce intelligence across promotion readiness, attrition risk, job levels, and workforce demographics.*

<br/>

![HR Dashboard Preview](HR_Analysis.jpg)

---

</div>

## 📌 Table of Contents

- [Overview](#-overview)
- [Key Metrics at a Glance](#-key-metrics-at-a-glance)
- [Deep-Dive Insights](#-deep-dive-insights)
  - [Workforce Composition](#1-workforce-composition)
  - [Promotion Landscape](#2-promotion-landscape)
  - [Service Tenure Distribution](#3-service-tenure-distribution)
  - [Job Level Breakdown](#4-job-level-breakdown)
  - [Attrition Status](#5-attrition-status)
  - [Distance from Office](#6-distance-from-office)
- [Dashboard Features](#-dashboard-features)
- [Filters & Interactivity](#-filters--interactivity)
- [Data Source](#-data-source)
- [Key Takeaways & Recommendations](#-key-takeaways--recommendations)
- [Getting Started](#-getting-started)
- [Contributing](#-contributing)

---

## 🔍 Overview

This **Power BI HR Analytics Dashboard** provides a 360° view of the workforce across six critical dimensions: headcount, gender distribution, promotion eligibility, tenure, job levels, and distance from work. It is designed for **HR managers, business analysts, and C-suite decision-makers** who need fast, reliable, and visual workforce intelligence.

> **1,470 employees. Thousands of data points. One dashboard.**

---

## 📊 Key Metrics at a Glance

| Metric | Value | Context |
|---|---|---|
| 👥 **Total Employees** | **1,470** | Full workforce headcount |
| 👨 **Male Employees** | **882 (60%)** | Majority gender |
| 👩 **Female Employees** | **588 (40%)** | Minority gender — highlights diversity gap |
| ✅ **Due for Promotion** | **72 (4.9%)** | Employees who meet promotion criteria |
| ⏳ **Not Due for Promotion** | **1,398 (95.1%)** | Majority ineligible currently |
| 🟢 **On Service (Active)** | **1,353 (92%)** | Actively employed |
| 🔴 **Retrenched** | **117 (8%)** | Employees who have left / been let go |

---

## 🔬 Deep-Dive Insights

### 1. Workforce Composition

```
Total Employees: 1,470
├── Male   ██████████████████████████████ 882  (60%)
└── Female ████████████████████          588  (40%)
```

The workforce is **predominantly male at 60%**, with female employees comprising 40%. This gender gap — while not extreme — represents a meaningful opportunity to review **hiring, retention, and inclusion strategies** to build a more balanced workforce.

---

### 2. Promotion Landscape

```
Promotion Eligibility Breakdown
├── Due for Promotion     ██ 72    (4.9%)
└── Not Due for Promotion ████████████████████████████████ 1,398 (95.1%)
```

Only **4.9% of employees (72 individuals)** are currently flagged as due for promotion. This is a relatively conservative promotion rate that could indicate:

- 📋 A **structured, merit-based** promotion pipeline
- ⚠️ Potential **talent bottlenecks** if high performers are stagnating
- 🔎 Opportunity to **review criteria** and identify overlooked candidates

**Recommendation:** Cross-reference the 72 eligible employees with their tenure and performance data to fast-track critical talent retention efforts.

---

### 3. Service Tenure Distribution

The **top 5 tenure brackets** by headcount:

| Service Years | Employee Count | Visual |
|---|---|---|
| **5 years** | 196 | `████████████████████` |
| **1 year** | 171 | `█████████████████` |
| **3 years** | 128 | `█████████████` |
| **2 years** | 127 | `████████████` |
| **10 years** | 120 | `████████████` |

**Key Observation:** The largest cohort has **5 years of service**, suggesting a strong mid-tenure workforce. The significant number of **1-year employees** points to **recent hiring activity**, while the 10-year group represents a seasoned, institutional knowledge base that warrants **targeted retention programs**.

---

### 4. Job Level Breakdown

```
Total Employees by Job Level
Level 1  ████████████████████████████ 543
Level 2  ███████████████████████████  534
Level 3  ███████████                  218
Level 4  █████                        106
Level 5  ██                            69
```

| Level | Count | % of Workforce |
|---|---|---|
| Level 1 | 543 | 36.9% |
| Level 2 | 534 | 36.3% |
| Level 3 | 218 | 14.8% |
| Level 4 | 106 | 7.2% |
| Level 5 | 69 | 4.7% |

The pyramid structure is **healthy** — a large base of entry/mid-level employees with progressively fewer at senior tiers. However, the **sharp drop from Level 2 → Level 3** (534 → 218) warrants attention: this transition gap may indicate a **career advancement barrier** that's frustrating talent and driving attrition.

---

### 5. Attrition Status

```
Current Workforce Status
├── On Service  ████████████████████████████████████████████ 1,353 (92%)
└── Retrenched  ████                                           117  (8%)
```

An **8% retrenchment rate (117 employees)** is worth monitoring closely. While the current 92% active workforce is strong, attrition analysis should drill into:

- 🔺 Which **job levels** are most affected
- 🔺 Whether **tenure length** correlates with attrition
- 🔺 Whether **distance from office** contributes to departure decisions

---

### 6. Distance from Office

```
Employee Distribution by Commute Distance
■ Very Close   940 employees  (63.95%)
■ Close        301 employees  (20.48%)
■ Very Far     229 employees  (15.58%)
```

Nearly **two-thirds of employees live very close** to the office, which is a strong indicator of **low commute-related attrition risk** for the majority. However, the **15.58% who live very far (229 employees)** may be candidates for:

- 🏠 **Remote or hybrid work** policy consideration
- ⚠️ **Higher attrition risk** — worth monitoring against retrenchment data
- 🚌 **Transport allowance or support programs**

---

## ✨ Dashboard Features

- 📊 **KPI Summary Cards** — Instant top-line metrics
- 📉 **Bar Charts** — Service tenure and job level distribution
- 🍩 **Donut Chart** — Distance status proportional breakdown
- 🎛️ **Interactive Slicers** — Filter by Age, Gender, and Attrition
- 🔄 **Cross-filtering** — All visuals respond to slicer selections dynamically

---

## 🎛️ Filters & Interactivity

The dashboard supports three slicer dimensions:

| Filter | Options |
|---|---|
| **Age** | 18 through 26+ (multi-select checkboxes) |
| **Gender** | Female / Male |
| **Attrition** | Yes / No |

All charts and KPI cards update **in real time** as filters are applied, enabling segmented analysis for any HR scenario.

---

## 📁 Data Source

| Item | Detail |
|---|---|
| **File** | `HR_Analytics_Data.csv` |
| **Records** | 1,470 employee rows |
| **Tool** | Microsoft Power BI Desktop |
| **Key Fields** | Age, Gender, Attrition, Job Level, Years at Company, Distance from Home, Promotion Status |

---

## 💡 Key Takeaways & Recommendations

| # | Insight | Action |
|---|---|---|
| 1 | **Gender imbalance (60/40 M/F)** | Review recruitment pipelines and inclusion programs to attract more female talent |
| 2 | **Only 4.9% promotion-eligible** | Audit promotion criteria — ensure high performers at Levels 2 and 3 are not being blocked |
| 3 | **Level 2→3 bottleneck** | Create structured career development tracks bridging mid-level employees upward |
| 4 | **8% retrenchment** | Conduct exit interview analysis — identify preventable turnover patterns |
| 5 | **15.6% very far from office** | Assess remote work policies or relocation support to reduce distance-driven attrition |
| 6 | **Large 1-year cohort** | Implement strong onboarding and 90-day engagement programs to convert new hires into long-term employees |

---

## 🚀 Getting Started

### Prerequisites

- [Power BI Desktop](https://powerbi.microsoft.com/en-us/desktop/) (free)
- The CSV data file: `HR_Analytics_Data.csv`

### Steps

```bash
# 1. Clone this repository
git clone https://github.com/yourusername/hr-analytics-dashboard.git

# 2. Open Power BI Desktop

# 3. Load the data source
File → Get Data → Text/CSV → Select HR_Analytics_Data.csv

# 4. Open the .pbix file (if included)
File → Open Report → Browse → select the .pbix file

# 5. Refresh data if needed
Home → Refresh
```

---

## 🤝 Contributing

Contributions, suggestions, and improvements are welcome!

1. Fork this repository
2. Create a feature branch (`git checkout -b feature/new-insight`)
3. Commit your changes (`git commit -m 'Add attrition trend analysis'`)
4. Push to the branch (`git push origin feature/new-insight`)
5. Open a Pull Request

---

<div align="center">

---

**Built with ❤️ using Microsoft Power BI**

*Transforming raw HR data into workforce intelligence*

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-0077B5?style=flat&logo=linkedin)](https://linkedin.com)
[![GitHub](https://img.shields.io/badge/GitHub-Follow-181717?style=flat&logo=github)](https://github.com)

</div>
