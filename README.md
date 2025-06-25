# AI-job-market-Analysis

# 🌐 Global AI Job Market & Salary Trends – 2025

This project analyzes the global AI job market and salary trends in 2025 using a fully interactive Power BI dashboard. It provides insights into salary patterns, job opportunities, hiring preferences, required skills, and the influence of company size, job type, and education level.

## 📊 Dashboard Highlights

🔹 **Average Salary Overview** – Explore the global average salary for AI jobs.  
🔹 **Job Trends Over Time** – See monthly job posting trends to identify demand shifts.  
🔹 **Salary by Experience, Education & Job Type** – Understand how qualifications impact pay.  
🔹 **Hiring Trends by Company Size** – Discover how small, medium, and large companies are hiring.  
🔹 **Remote Work Insights** – Analyze distribution of on-site, hybrid, and remote roles.  
🔹 **Top Paying Locations** – Visualize which countries pay the most for AI talent.  
🔹 **Skills in Demand** – Identify the top 5 skills with the highest salary association.  
🔹 **Industry & Job Type Comparison** – Compare salary and job counts across industries.

## 📁 Dataset

- Source: [Kaggle – AI Jobs Dataset (2025)](https://www.kaggle.com/)
- Rows: 15,000+ AI job listings
- Cleaned & processed in Python (Pandas)

### Key Fields Used

- `salary_in_usd`
- `experience_level`
- `employment_type` (Full-time, Contract, etc.)
- `remote_ratio`
- `company_size`
- `job_title`, `skills`, `education_required`
- `company_location`, `job_posted_date`, etc.

---

## 🧹 Data Preparation & Feature Engineering

The dataset was pre-cleaned. Minor wrangling was done to:

- Convert skill strings into individual rows for skill-based analysis  
- Normalize currencies to USD  
- Group job titles into broader categories  
- Engineer new columns for `job_type`, `experience_level`, and `education_category`

---

## ⚙️ Tools & Technologies

- **Power BI**: Dashboard creation, DAX calculations, data modeling  
- **Python (Pandas)**: Feature engineering and data transformation  
- **Canva / PowerPoint**: Presentation of findings

---

## 📈 Business Questions Addressed

1. What is the average AI salary in 2025, and how does it vary by experience level?
2. Which countries and companies offer the highest AI job salaries?
3. How are AI jobs distributed across remote, hybrid, and on-site types?
4. What skills are most associated with high-paying jobs?
5. How do education level and experience influence hiring trends?
6. What industries and company sizes are hiring the most AI professionals?
7. What are the month-over-month trends in AI job postings?

---

## 🧠 Key Insights

- **Top-paying countries**: Switzerland, Denmark, Norway, and the U.S.  
- **Most in-demand skills**: Statistics, SQL, R, AWS, Tableau  
- **Remote work**: 33% of AI jobs are remote, with steady hybrid demand  
- **Education trends**: Bachelor's and Master's degrees dominate the job market  
- **Company sizes**: Hiring is evenly split among small, medium, and large companies

---

## 📌 Final Thoughts

This dashboard empowers job seekers, recruiters, and policy makers with clear insights into the global AI employment landscape. It highlights where demand is growing, what skills to learn, and how to make informed decisions in a competitive tech world.

---

## 🔗 Live Dashboard

➡️ [View Interactive Power BI Dashboard](https://app.powerbi.com/view?r=eyJrIjoiOTdmYjJiZDMtOGMyNy00Mjg0LWFmYmEtOTEyNjY2MGEyMTBmIiwidCI6ImIyODg4MjkyLTMxZGQtNDhkZi05MmY4LTRhYjUwYTczMTg3NSJ9)



