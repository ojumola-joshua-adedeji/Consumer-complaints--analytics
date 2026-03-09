
An end-to-end interactive Power BI dashboard analysing **consumer financial complaint trends** across products, companies, and U.S. geographies — built using real-world data from the **Consumer Financial Protection Bureau (CFPB)**.

This project simulates the kind of compliance and customer experience analytics work done inside financial institutions and consulting firms — from raw data ingestion through to executive-ready insight delivery.

---

## 🎯 Business Problem

Financial companies receive thousands of consumer complaints each year, but without structured analytics, patterns go undetected. This dashboard answers critical business questions:

- Which **products and issues** generate the most complaints?
- Which **companies** have the worst resolution rates?
- How have complaints **trended over time** — and are they getting worse?
- Which **U.S. states** are most affected?

---

## 📂 Explore the Dashboard

> 📥 **The full interactive Power BI file is included in this repo.**  
> Download `PowerBI_Report.pbix` and open it in [Power BI Desktop](https://powerbi.microsoft.com/desktop/) (free) to explore all pages, filters, and drill-downs interactively.

---

## 📌 Key Findings

| Insight | Finding |
|---|---|
| 📈 Complaint growth | Complaints increased steadily from **2019 to 2024** |
| 🏦 Top product categories | **Credit & mortgage products** account for **65%+** of all complaints |
| 📍 Highest volume states | **California and Texas** reported the most complaints nationally |
| ⚠️ Resolution disparity | Resolution rates **vary significantly** between companies — revealing accountability gaps |

---

## ⚙️ Technical Approach

### Data Pipeline
```
CFPB Raw Dataset → Power Query (Cleaning & Transformation) → Data Model → DAX Measures → Dashboard
```

### Data Cleaning (Power Query)
- Removed duplicates and standardised inconsistent category labels
- Handled null values across complaint status and resolution fields
- Parsed and formatted date columns for time-intelligence calculations
- Filtered irrelevant complaint records to improve model performance

### DAX Measures Built
- Total Complaints, YoY Complaint Growth %
- Resolution Rate %, Timely Response Rate %
- Complaints by Product Category (ranked)
- State-level complaint density calculations

---

## 📁 Repository Structure

```
Consumer-complaints-analytics/
│
├── PowerBI_Report.pbix          # Full interactive Power BI dashboard
├── PowerPoint_Report.pptx       # Slide deck version with narrative insights
├── data/
│   └── consumer_complaints_cleaned.csv   # Cleaned CFPB dataset
└── README.md
```

---

## 🛠️ Tools & Technologies

| Tool | Usage |
|---|---|
| **Power BI Desktop** | Dashboard design & visualisation |
| **DAX** | Calculated KPIs and measures |
| **Power Query** | Data cleaning & transformation |
| **CFPB Public Dataset** | Source data (real-world financial complaints) |

---

##  What This Project Demonstrates

✅ End-to-end analytics workflow — from messy raw data to polished executive dashboard  
✅ Compliance-oriented thinking — analysing resolution rates and accountability gaps  
✅ Real-world dataset handling — 60,000+ records cleaned and modelled  
✅ Stakeholder communication — structured findings with clear business recommendations  
✅ Power BI best practices — dynamic filters, drill-downs, and layered reporting

---

##  Recognition

This project was submitted to the **Onyx Data DNA Challenge** — a competitive community analytics challenge where real-world datasets are used to test end-to-end analytical and visualisation skills.

---

## 👤 About the Author

**Joshua Ojumola** — Data Analyst specialising in Power BI dashboards and SQL data pipelines.

📧 joshuaojumola@gmail.com  
💼 [LinkedIn](https://www.linkedin.com/in/ojumola-adedeji-758471381/)  
🐙 [GitHub Portfolio](https://github.com/ojumola-joshua-adedeji)

> *Open to freelance analytics projects, data analyst roles, and collaborations. Let's connect.*

---

*Part of an active data analytics portfolio — more projects at [github.com/ojumola-joshua-adedeji](https://github.com/ojumola-joshua-adedeji)*
 to collaborate or discuss data solutions
