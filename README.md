# Social Anxiety Data Analysis & Dashboard

Welcome to my portfolio project! In this repository, I share the data analysis and interactive dashboard I created for one of my assessments in my **Higher Diploma in Data Analysis**. 

As a **neuropsychologist**, my goal was to combine my clinical background with data science. I wanted to show how lifestyle, demographic and clinical variables can help us understand a complex mental health condition like Social Anxiety.

This project uses a synthetic dataset from Kaggle with over 10,000 records. Even though the data is simulated, the results and correlations are incredibly similar to real clinical situations that I see every day in my clinic. 
The main focus was technical like transform raw data into visual and strategic insights to help healthcare professional and stakeholders make good decisions.

## Technical Steps & Features

*   **Data Modeling (Star Schema):** I organized the raw data by splitting the large table into Fact and Dimension tables (*Patient, LifeStyle, and Clinical*) to optimize Excel's performance.
*   **ETL & Data Cleaning:** I cleaned the numbers, normalized the columns, and created simple logical groups (like age ranges and activity levels) to make the data easy to read.
*   **Excel Syntax:** I adapted all my formulas to the English version of Excel, switching from semicolons to commas as separators.
*   **Storytelling & Dashboarding:** I built a fully interactive and accessible dashboard using high-contrast colors, dynamic *Slicers*, and clear charts (like horizontal bars for occupations and lines for caffeine trends).

## Key Insights & Real-World Actions

Instead of just creating pretty graphs, this analysis allowed me to design practical strategies for the healthcare and corporate sectors:

1. **The Therapy Paradox (Managing Initial Sessions):** The dashboard captured a real phenomenon from clinical literature (Bakkeli, 2025) — stress levels actually go up when patients start going to more therapy. Because I see this all the time in my clinic, I know that clinics can use this data for psychoeducation. If we warn patients in their first sessions that facing hard topics brings temporary stress, they won't give up on therapy easily (reducing dropout rates).
2. **Corporate Wellness:** I found that a bad diet, too much coffee, and no exercise make anxiety much worse in specific jobs. HR teams can use this data to build better wellness programs at work.
3. **Somatic Intervention:** I mapped the connection between a high heart rate and recent stressful life events, opening doors for using biofeedback and self-regulation tools with wearables (like smartwatches).

## 📂 Repository Structure

*   `social-anxiety-analysis-dashboard.xlsx`: The complete Excel file with the Star Schema model, data cleaning, and the interactive dashboard.
*   `social-anxiety-project-report.pdf`: The official written report explaining the methodology, data quality, and documentation.

## 🛠️ Tools Used
*   Microsoft Excel (Data Modeling, Power Query/ETL, Power Pivot, DAX, Dashboarding)
*   Markdown (for this documentation)
