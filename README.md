# HR Analytics EDA Project 📊

This project focuses on **Exploratory Data Analysis (EDA)** of job listings in the analytics industry. The dataset used consists of job postings from multiple days, scraped from job portals of companies based in Hong Kong. The goal is to extract meaningful insights for HR departments to better understand hiring patterns, industry trends, job qualifications, and career levels.

## 🔍 Project Overview

Human Resource (HR) teams often handle massive volumes of job-related data. This project helps analyze:
- Hiring trends across analytics roles (Data Scientist, Data Analyst, ML Engineer, etc.)
- Most active recruiting companies
- Common job types and qualifications
- Career level distribution (Entry, Mid, Senior)
- Domain-wise job availability

## 📁 Dataset Details

- Combined dataset from 6 separate job listing days
- Fields include: `Job Title`, `Company`, `Salary`, `Job Type`, `Qualification`, `Experience`, `Industry`, `Date Posted`, etc.
- Focused on Hong Kong-based companies in the analytics sector

## 🛠️ Tools Used

- **Power BI**: Data cleaning, transformation, and visualization
- **M Language**: To create date tables
- **Microsoft Excel**: For basic formatting and validation

## 🔄 Steps Involved

1. **Data Cleaning**
   - Removed unnecessary columns and null values
   - Standardized categorical data (e.g., Qualification fields)
   - Replaced incorrect values (e.g., `-1` experience → `1`)

2. **Data Transformation**
   - Changed column data types (e.g., Experience to numeric)
   - Created a custom date table using M Language

3. **Visual Analytics**
   - Built dashboards to explore:
     - Career level distribution
     - Most in-demand job roles
     - Top hiring companies
     - Domain-specific insights
     - Qualification requirements

## 📌 Key Insights

- **Total Jobs**: 1,979 from 719 companies
- **Top Roles**: Data Scientist (1,597 jobs), Data Analyst (286 jobs)
- **Top Companies**: HKT, Michael Page
- **Most Jobs**: At middle career level (51.24%)
- **Most Preferred Qualification**: Degree
- **Most Common Job Type**: Temporary/Contract


## 📊 Dashboard Preview

- Summary Statistics Page
- Job Summary by Career Level
- Top Companies by Job Count
- Role-wise and Domain-wise Trends
- Qualification Analysis

## 📝 Conclusion

This project demonstrates how HR departments can leverage data analytics tools like Power BI to derive valuable hiring insights. It simplifies recruitment decisions by identifying which skills and qualifications are in demand, which roles are most common, and how career levels vary by company or domain.

## 📂 Files Included

- `EDA_HR_Project_Report.docx` - 2-page summary report
- Power BI Dashboard file (optional if added)

  ## Author
  Vijay appisetty
