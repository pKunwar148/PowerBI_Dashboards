# Data Jobs Dashboard 2.0 | Power BI Project


![Data Jobs Dashboard Overview](/images/Project2Vedio.gif)
## 📊 Project Overview

This Power BI project analyzes the data job market using a real-world dataset of data-related job postings. The dashboard was created as part of my hands-on learning from the **Power BI for Data Analytics - Full Course for Beginners** by **Luke Barousse**.

While the main dashboard was built by following the course structure, I expanded the project by adding additional analysis pages focused on salary trends, company-level hiring, job schedule types, skill requirements, salary relationships, interactive category analysis, and estimated take-home pay.

The goal of this project was to transform raw job posting data into an interactive dashboard that helps job seekers, students, and career switchers understand the data job market more clearly.

---

## 🎯 Project Objective

The main objective of this dashboard is to answer important questions about the data job market, such as:

- What are the most in-demand data skills?
- Which data roles have the highest number of job postings?
- Which data jobs offer the highest median salaries?
- How do salaries vary across companies?
- How do job schedule types differ across roles?
- Do roles requiring more skills also offer higher salaries?
- How much estimated salary may remain after applying a user-defined deduction rate?

---

## 📁 Dashboard File

You can find the Power BI dashboard file here:

[Data Jobs Dashboard 2.0.pbix](/Data_Jobs_v2/Data_Jobs_Dashboard_2.pbix)


---

## 🛠️ Tools Used

- Power BI Desktop
- Power Query
- DAX
- Data Modeling
- Excel / CSV Dataset
- GitHub

---

## 🧠 Skills Showcased

This project helped me apply and improve the following skills:

### Power BI Skills

- Data cleaning and transformation using Power Query
- Data modeling and relationship building
- Creating calculated columns and DAX measures
- Designing interactive dashboards
- Creating KPI cards, bar charts, tables, and scatter plots
- Using slicers and filters for user-driven analysis
- Creating dynamic visuals using field parameters
- Building what-if style analysis using parameter controls
- Improving dashboard layout, readability, and storytelling

### Data Analytics Skills

- Exploratory data analysis
- Salary analysis
- Job market analysis
- Skill demand analysis
- Company-level comparison
- Trend and distribution analysis
- Data storytelling
- Business insight generation

---

## 📌 Dashboard Overview

The main dashboard provides a high-level summary of the data job market.

![Dashboard Overview](/images/Project2_Page1.png)

### Key Metrics

The dashboard highlights important KPIs including:

- **Total Job Count:** 479K
- **Average Skills Per Job:** 4.8
- **Median Yearly Salary:** $113K
- **Median Hourly Salary:** $48

### Main Dashboard Features

The overview page includes:

- Top skills in data jobs
- Top paying data jobs
- Job title filter
- Country filter
- Clear slicer button
- Skill popularity comparison
- Salary comparison by job title

From the dashboard, Python and SQL appear as two of the most frequently requested skills, showing their strong demand in the data job market. The salary analysis also shows that senior and specialized technical roles generally offer higher median salaries.

---

## 📈 Additional Analysis Added

In addition to the main dashboard, I added multiple analysis pages to explore the dataset more deeply.

---

## 1. Salary Analysis

![Salary Analysis](/images/Project2_SalaryAnalysis.png)

This page focuses on understanding salary patterns across data roles.

### What This Page Shows

- Top paying jobs based on median salary
- Comparison of yearly and hourly-adjusted salary
- Distribution of hourly salary ranges
- Job count across different hourly salary groups

### Key Insight

Senior and specialized roles such as **Senior Data Scientist**, **Machine Learning Engineer**, **Senior Data Engineer**, and **Software Engineer** show some of the highest median salaries. The hourly salary distribution also shows that most hourly jobs are concentrated in lower-to-mid hourly pay ranges, while very high hourly salary ranges have fewer job postings.

---

## 2. Company Analysis

![Company Analysis](/images/Project2_CompanyStat.png)

This page analyzes companies appearing in data job postings.

### What This Page Shows

- Top companies hiring for data roles
- Job count by company
- Median salary of the top companies
- Company-level comparison of hiring volume and compensation

### Key Insight

Some companies appear frequently in data job postings, showing stronger hiring activity in the dataset. However, the companies with the highest job counts are not always the same companies offering the highest median salaries. This helps job seekers compare both opportunity volume and compensation potential.

---

## 3. Job Type / Schedule Type Analysis

![Job Type Analysis](/images/Project2_JopType.png)

This page compares job schedule types across major data roles.

### What This Page Shows

- Full-time roles
- Contractor roles
- Internship roles
- Part-time roles
- Per diem roles
- Job count by schedule type
- Salary comparison by schedule type

### Key Insight

Full-time roles dominate the data job market across Data Analyst, Data Engineer, and Data Scientist positions. Contract, internship, and part-time roles appear in smaller numbers, but salary patterns vary depending on the role and schedule type.

---

## 4. Skill vs Salary Analysis

![Skill vs Salary Analysis](/images/Project2_SkillvsSlary.png)

This page explores the relationship between skill requirements and salary.

### What This Page Shows

- Skill count by job title
- Job count by job title
- Median yearly salary by role
- Skills per job by role
- Relationship between skills required and salary
- Salary comparison by skill count

### Key Insight

Roles requiring a higher number of skills generally show higher salary potential, but the relationship is not perfectly linear. For example, senior and engineering-focused roles often require more skills and tend to have higher median salaries, while some analyst roles require fewer skills and have lower median salary levels.

This page helped me better understand how skill requirements can influence compensation across different data roles.

---

## 5. Interactive Category and Measure Analysis

![Interactive Analysis](/images/Project2_interactive_parameters.gif)

This page adds more interactivity by allowing users to switch between different categories and measures.

### What This Page Shows

Users can analyze the data by selecting categories such as:

- Job Title
- Skills
- Country
- Company

Users can also switch between measures such as:

- Job Count
- Median Yearly Salary

### Key Insight

This interactive page makes the dashboard more flexible because users can explore the same dataset from different angles without needing separate static visuals for every category. It improves the user experience and makes the dashboard more useful for self-guided analysis.

---

## 6. Estimated Take-Home Pay Analysis

![Take Home Pay Analysis](/images/Project2_SalaryDeduction.gif)

This page estimates how much salary may remain after applying a user-defined deduction rate.

### What This Page Shows

- Median yearly salary by job title
- Estimated take-home pay after deduction
- Adjustable deduction rate parameter
- Comparison between gross salary and estimated take-home salary

### Important Note

This is not a tax calculator. It is an estimated deduction-based analysis that allows users to adjust the deduction percentage and compare potential salary differences across roles.

### Key Insight

This page helps users think beyond gross salary and understand how deductions can affect estimated take-home pay. It adds a more practical financial perspective for job seekers comparing different roles.

---

## 🔍 Key Insights from the Dashboard

Some of the major insights from this project include:

- Python and SQL are among the most in-demand skills in data-related jobs.
- Senior and specialized technical roles tend to have higher median salaries.
- Data Engineer, Data Analyst, and Data Scientist roles have the highest job counts in the dataset.
- Full-time roles dominate the data job market compared to contract, internship, and part-time roles.
- Companies with the most job postings do not always offer the highest median salaries.
- Roles requiring more skills often have higher salary potential, especially engineering and senior-level roles.
- Interactive filters and parameters make the dashboard easier to explore from different perspectives.
- Estimated take-home pay analysis gives a more realistic view of compensation after deductions.

---

## 📚 What I Learned

Through this project, I gained practical experience in:

- Importing and transforming data in Power BI
- Cleaning data using Power Query
- Creating relationships between tables
- Building DAX measures for analysis
- Designing an interactive dashboard layout
- Creating salary, company, skill, and job type analysis pages
- Using slicers, buttons, and parameters to improve interactivity
- Presenting insights clearly using visuals
- Building a Power BI project suitable for a data analytics portfolio

This project helped me understand how Power BI can be used not just for visualization, but also for real-world business and career-focused analysis.

---

## 🚀 How to Use This Dashboard

1. Download the `.pbix` file from this repository.
2. Open it using Power BI Desktop.
3. Use the slicers to filter by job title and country.
4. Navigate through the different dashboard pages.
5. Explore salary trends, company analysis, skill demand, job types, and estimated take-home pay.
6. Review the data model, Power Query steps, and DAX measures to understand the backend structure.

---

## 🙏 Credits

This project was created while following the **Power BI for Data Analytics** by **Luke Barousse**.

The course was used as a learning reference. I also added my own analysis pages and insights to expand the project and strengthen my understanding of Power BI, dashboard design, and data analytics.

---

## 👤 Author

**Poonam Kunwar**  
Master’s Student in Engineering Management  
Data Analytics | Business Intelligence | Power BI | SQL | Supply Chain Analytics