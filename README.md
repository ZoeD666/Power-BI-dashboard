# New Zealand Infrastructure Project Monitoring Dashboard

This Power BI dashboard enables interactive monitoring of major infrastructure projects across New Zealand, using official open government data. It helps identify project risks, analyse funding structure, and support strategic planning.

## 📌 Purpose & Value

The dashboard provides:

- **Project Overview**: Summarises infrastructure projects by budget, location, duration, and status
- **Risk Alerts**:
  - Identify projects with **excessive budgets** and **extended durations**
  - Highlight **delayed starts** or stalled projects
- **Analytical Insights**:
  - Compare regional investment patterns
  - Assess budget allocation across agencies
  - Support government or stakeholder reporting

## 📊 Dashboard Highlights

- **KPI Cards**: Total Projects, Total Budget, Projects > 36 months, Projects > $200M
- **Status Pie Chart**: Compare "Planned" vs "Started" projects
- **Budget Bar Chart**: Regional distribution of total budget
- **Scatter Plot**: Budget vs Duration – to detect high-risk projects
- **Quarterly Trend Line**: Expected start timeline overview
- **Risk Table**: Projects over $200M and longer than 36 months

## 🧮 Data Filtering & Transformation (Power Query)

- Included projects with planned start from **2021 onwards**
- Filtered to show **30 projects** with budgets between **$25M and $250M**
- Added fields:
  - `Duration (Months)`
  - `BudgetMid (Million)`
  - `IsStart` (true if started before Jan 2024)
- Cleaned dataset, removed duplicates, created a primary key

## 🛠 Tools & Techniques

- Power BI Desktop
- Power Query Editor
- DAX measures and calculated columns
- Interactive slicers (Region, Status, Budget, Duration)
- Dashboard design with multiple chart types

## 📁 Files

- `NZ_Infrastructure_Database.csv`: Source data from data.govt.nz
- `INFRASTRUCTURE PROJECT MONITORING DASHBOARD.pbix`: Power BI file
- Optional screenshots (PDF)

## 📄 Data Source & License

- **Source**: [New Zealand Infrastructure Pipeline](https://catalogue.data.govt.nz/dataset/new-zealand-infrastructure-pipeline)
- **Publisher**: New Zealand Infrastructure Commission – Te Waihanga
- **License**: NZGOAL – NZ Government Open Access Licence

---
