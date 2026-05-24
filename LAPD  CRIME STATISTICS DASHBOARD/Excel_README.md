# Excel Projects 📗

This repository contains Excel dashboards and reports built using real-world datasets. Each project demonstrates end-to-end data analysis — from data ingestion and cleaning through to insight delivery and dashboard design.

---

## Projects

### 1. LAPD Crime Statistics Dashboard

**Dataset:** LAPD Open Data — Crime Records 2020 to Present  
**Tool:** Microsoft Excel (Power Query, Pivot Tables, Charts)  
**Records Analysed:** 974,477+

---

#### Dashboard Screenshots

<img width="896" height="657" alt="image" src="https://github.com/user-attachments/assets/7e7e7a07-89a7-4838-a750-c3c06773535f" />


<img width="891" height="311" alt="image" src="https://github.com/user-attachments/assets/deaaa1aa-8688-4f33-978e-6bae4f3b4986" />

---

#### Overview

This dashboard visualises over 974,000 LAPD crime records from 2020 to the present, built entirely in Microsoft Excel using Power Query and Pivot Tables. The report **automatically refreshes** whenever new data files are added to the source folder — no manual re-work required.

The goal was to give a clear, at-a-glance view of crime trends, victim demographics, and weapon usage patterns across Los Angeles from 2020 onwards.

---

#### Key Insights

- **974,477 total crimes** recorded from 2020 to present across all LAPD divisions

- Crime **peaked in early 2022 at approximately 9,000 incidents per month** before declining significantly to around 3,500 per month by late 2024 — a drop of over 60%

- **Male victims (394,539)** represent the largest recorded group, followed by female victims (350,930) and non-binary/other (92,893)

- **Strong-arm tactics** (hands, fists, feet or bodily force) are overwhelmingly the most common weapon type at **174,296 incidents** — more than 4x the next category

---

#### How It Was Built

**1. Data Ingestion — Power Query Folder Connection**

Connected to the LAPD open dataset using Power Query's **Get Data → Folder** feature, allowing multiple monthly CSV files to be combined automatically into a single dataset. Adding new monthly files to the source folder refreshes the entire report instantly — no manual copy-pasting of data required.

**2. Data Cleaning — Power Query Transformations**

Applied the following transformations in Power Query before loading data into Excel:

- Trimmed whitespace from all text columns
- Standardised date formats for consistent time analysis
- Removed null and blank rows from key fields
- Renamed columns for clarity and consistency

**3. Analysis — Pivot Tables**

Built Pivot Tables to aggregate crime counts by:
- Month and year (for trend analysis)
- Victim sex (for demographic breakdown)
- Weapon type (for frequency ranking)

Pivot Tables allow fast slicing and filtering without touching or altering the raw data.

**4. Visualisation — Dynamic Charts**

Designed three chart types, all connected to Pivot Tables so they **update automatically on data refresh:**

| Chart Type | What It Shows |
|---|---|
| Line Chart | Monthly crime trend from 2020 to 2024 |
| Column Chart | Total victims reported by sex |
| Horizontal Bar Chart | Top weapon types by frequency |

---

#### Excel Features Used

- ✅ Power Query — Folder connection for automatic data ingestion
- ✅ Power Query — Data cleaning and transformation steps
- ✅ Pivot Tables — Dynamic aggregation and slicing
- ✅ Pivot Charts — Auto-updating visualisations
- ✅ KPI Card — Total crimes headline figure
- ✅ Dashboard layout — Single-sheet professional view

---


