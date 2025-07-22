# Data Jobs Dashboard w/ Power BI

## Introduction

This dashboard was created for **Job Seekers, Job Transitioners, and Job Swappers** to solve a common problem: information about the data job market is scattered and hard to grasp. Using a real-world dataset of 2024 data science job postings (including titles, salaries, and locations), this project provides a single, easy-to-use interface to explore market trends and compensation.

### Dashboard File
You can find the file for the dashboard here: [`Data_Jobs_Dashboard.pbix`](/Data_Jobs_Dashboard_1/Data_jobs_dashboard.pbix).  

## Skills Showcased

This project was a journey through key Power BI features. Here's a look at what I have learnt:

-   **⚙️ Data Transformation (ETL) with Power Query:** Cleaned, shaped, and prepared the raw data for analysis by handling blanks, changing data types, and creating new columns.
-   **🧮 Implicit Measures:** Formulated measures to derive key insights and KPIs like `Median Yearly Salary` and `Job Count`.
-   **📊 Core Charts:** Utilized **Column, Bar, Line,** and **Area Charts** to compare job counts and track trends over time.
-   **🗺️ Geospatial Analysis:** Leveraged **Map Charts** to visualize the global distribution of jobs.
-   **🔢 KPI Indicators & Tables:** Used **Cards** to display key metrics and **Tables** to provide granular, sortable data.
-   **🎨 Dashboard Design:** Designed an intuitive and visually appealing layout, exploring both common and uncommon chart types to best tell the data story.
-   **🖱️ Interactive Reporting:**
    -   **Slicers:** To dynamically filter the report by Job Title.
    -   **Buttons & Bookmarks:** To create a seamless navigation experience.
    -   **Drill-Through:** To navigate from a high-level summary to a contextual, detailed view.
---

## Dashboard Overview

*This report is split into two distinct pages to provide both a high-level summary and a detailed analysis.*

### Page 1: High-Level Market View

![Data Jobs Dashboard Page 1](/images/data_job_dashboard_1_page_1.jpg)  

This is our mission control for the data job market. It showcases key KPIs like total job count, median salaries, and top job titles to give us a quick understanding of what's happening in the job market at a glance.

### Overall Market Snapshot
- Total open positions: ~479 K

- Median pay across all roles: $113.3 K/year ($47.62/hour) (we use median here to account for outliers in some Science data job with almost 1mil USD salary)

- “Salary Star” rating: ★★★☆☆ (mid‑range competitiveness) based on my subjective judgement


### Job Trend

- Seasonal Hiring Trend (2024)
Peak hiring in spring/early summer (~50 K monthly openings)

- Slowdown in Q4 (dipping to ~35 K)

- Uptick again toward year‑end

Insight for a job seeker:

Hit the market in Q2–Q3 (April–September):

- Companies post the most data‑role openings then—your résumé will get in front of the largest number of recruiters.

- Apply, follow up, and schedule interviews during this “peak season.”

Use Q4 (October–December) strategically:

- With fewer openings, focus on upskilling (online courses, certifications) and expanding your network (conferences, meetups, LinkedIn).

- Refine your portfolio and interview prep so you’re ready for the next hiring burst in Q1.

Plan for Q1 (January–March):

- Many teams have fresh budgets and back‑to‑work momentum—early‑year applications can land you roles before the spring peak.

By aligning your search rhythm with hiring cycles—aggressive outreach in Q2–Q3, skill‑building in Q4, then another push in Q1—you’ll maximize both visibility and your readiness for top data‑job opportunities..


### Page 2: Job Title Drill Through

![Data Jobs Dashboard Page 2](/images/data_job_dashboard_1_page_2.jpg)  

This is the deep-dive page. From the main dashboard, we can drill through to this view to get specific details for a single job title, including salary ranges, work-from-home stats, top hiring platforms, and a global map of job locations.

---

## Conclusion

This dashboard showcases how Power BI can transform raw job posting data into a powerful tool for career analysis. It allows users to slice, filter, and drill through data to make informed decisions about their career paths.
