# Hospital-Analysis
Hospital-Analysis/
│
├── notebooks/           # Python/Jupyter notebooks or SQL scripts
│   └── Hospital_EDA.ipynb
│
├── dashboards/          # Power BI files, Excel dashboards, or PDFs
│   └── Hospital_Dashboard.pbix
│   └── Hospital_Report.pdf# Hospital Data Analysis  

# Hospital Data Analysis

## TL;DR
Analyzed hospital patient data to uncover trends in admissions, treatments, and costs using Python and SQL. Built dashboards and reports for better decision-making.

## Tools
Python (Pandas, Matplotlib, Seaborn), SQL, Excel

## Dataset
Hospital patient records (patient ID, age, gender, admission, discharge, treatment type, costs)

## Steps
1. Data Cleaning & Preprocessing: Removed missing values, handled duplicates.
2. Exploratory Data Analysis (EDA): Analyzed patient demographics, admission trends, common treatments.
3. SQL Analysis: Queries to summarize admissions per department, treatment costs, patient stay duration.
4. Visualization & Reporting: Created graphs & charts to highlight key insights.

## Key Results
- Identified busiest departments and peak admission times.
- Found average treatment costs and patient stay duration trends.
- Helped hospital management optimize resource allocation.

## How to Run
```bash
git clone git@github.com:poornamanikanta/hospital-analysis.git
cd hospital-analysis
pip install -r requirements.txt
jupyter notebook notebooks/Hospital_EDA.ipynb
