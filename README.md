# 📊 Job Market Analysis Dashboard

---

🔹 **1. Business Problem (Context):**  
The job market for data analysts is competitive and constantly evolving. Companies post thousands of job listings daily, each requiring different skills, tools, and qualifications.  
**Objective:** Analyze real-world job listing data to identify:
- Most in-demand skills
- Top hiring companies
- Geographical job distribution
- Salary posting trends  

This insight can help job seekers focus their skill development and allow recruiters to understand market trends.

---

🔹 **2. Your Role & Responsibilities:**  
I worked end-to-end on this project:
- **Data Collection:** Gathered job listings dataset in CSV format.  
- **Data Cleaning:** Removed duplicates, handled missing values, standardized city/company names.  
- **Feature Engineering:** Extracted skills from job descriptions (e.g., Python, SQL, Excel).  
- **Data Transformation:** Used Power Query to unpivot skill columns and prepare for visualization.  
- **Visualization:** Designed and built an interactive **Power BI dashboard** with bar charts, pie charts, maps, and line charts.  

---

🔹 **3. Tools & Techniques Used:**  
- **Python (Pandas):** Data cleaning & skill extraction from job descriptions.  
- **Power BI:** Dashboard creation and interactivity (filters, slicers, cards).  
- **Power Query:** Data shaping, column transformations, and unpivoting.  
- **Excel:** Quick checks on data quality.  

---

🔹 **4. Challenges & Solutions:**  
- **Challenge:** Skill columns were in wide format, making it hard to plot in Power BI.  
  **Solution:** Used Power Query’s “Unpivot Columns” to restructure data for better aggregation.  

- **Challenge:** Some job postings had incomplete location data.  
  **Solution:** Cleaned and standardized location fields, removed nulls before mapping.  

- **Challenge:** Salary trends data was inconsistent with date formatting.  
  **Solution:** Converted date columns into proper `datetime` format for accurate trend analysis.  

---

🔹 **5. Business Impact & Results:**  
✅ Identified **SQL, Python, and Excel** as the top skills in demand.  
✅ Discovered **Amazon, Adobe, and S&P Global** among the top hiring companies.  
✅ Mapped job postings to visualize demand hotspots across cities.  
✅ Created a clear salary posting trend line to show when job postings peak.  

This dashboard empowers **job seekers** to focus on the right skills and **recruiters** to understand market patterns, helping both parties make informed decisions.

---

## 📂 Project Files
| File | Description |
|------|-------------|
| `Job Market Dashboard.pbix` | Power BI dashboard file |
| `data_analyst_jobs.csv` | Cleaned job listings dataset |
| `job-market-analysis.ipynb` | Jupyter Notebook|
| `README.md` | Project documentation |

---
