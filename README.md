# Road Accident Dashboard – Level 2 Documentation

I'm thrilled to unveil my inaugural Excel project—a comprehensive Road Accident Dashboard covering 2021 & 2022! Using a robust dataset of 3.07 million rows across 21 fields, I built an interactive tool to transform raw data into actionable insights for road safety.

---

## Table of Contents

- [Project Overview](#project-overview)
- [What’s Inside?](#whats-inside)
- [Why It Matters](#why-it-matters)
- [Key Takeaways](#key-takeaways)
- [Project Environment & Workflow](#project-environment--workflow)
- [Dashboard Structure](#dashboard-structure)
- [How to Use](#how-to-use)
- [Acknowledgements](#acknowledgements)

---


## Project Overview

**Road Accident Dashboard** is an Excel-based dashboard that analyzes synthetic road accident data from 2021 and 2022. Sourced from Kaggle, this project processes over 307,000 rows (up to 3.07 million records) across 21 fields. It reveals patterns in accident severity, vehicle involvement, environmental conditions, and temporal trends—providing a clear view of high-risk areas to support data-driven decision-making.

---

## What’s Inside?

- **Primary KPIs:**
  - Total Casualties: 417,882
  - Accident Severity Breakdown: Fatal, Serious, and Slight (with percentage contributions)
  - Max Casualties by Vehicle Type: e.g., Cars account for 79.8% of incidents
- **Secondary Insights:**
  - Casualties segmented by vehicle type
  - Monthly trends (current vs. previous year)
  - Maximum casualties by road type
  - Casualty distribution by road surface
  - Analysis of casualty patterns by area/location and time (day/night)

---

## Why It Matters

This dashboard provides a clear snapshot of road accident impacts, supporting data-driven decisions for stakeholders such as the Ministry of Transport, Road Transport Department, Police Force, Emergency Services, and more. It turns raw data into life-saving insights that drive improvements in road safety policies and infrastructure investments.

---

## Key Takeaways

- **Data Mastery:**  
  Advanced skills in data cleaning, transformation, and visualization using Excel.
- **Insightful Analysis:**  
  In-depth understanding of accident trends and risk factors.
- **Interactive Storytelling:**  
  Engaging dashboard design with slicers, timelines, and drill-down features.
- **Practical Impact:**  
  Empowering stakeholders with actionable insights for targeted safety interventions.

---

## Project Environment & Workflow

### File & Data Specifications
- **Format:** Excel Workbook (.xlx)
- **Dataset:** Synthetic data from Kaggle (307,000+ rows, 21 fields)
- **Performance:** Optimized for handling up to 3.07 million records
- **Excel Version:** Office 365
- **Dataset:** Download the dataset

### Workflow Phases

1. **Data Scrubbing:**  
   - Validate columns for nulls and errors.
   - Correct typos (e.g., “fetal” → “fatal” in 49 instances) and standardize date formats (DD/MM/YYYY).

2. **Data Transformation:**  
   - Derive Month and Year columns:
     ```excel
     =TEXT(B2, "mmm")
     =TEXT(B2, "yyyy")
     ```
   - Propagate formulas using the fill handle (Ctrl+D).
   - Validate that the dataset includes exactly 12 unique months and only the years 2021–2022.

3. **Analytical Processing:**  
   - Build multiple PivotTables to calculate key metrics (total casualties, severity breakdown, vehicle analysis, etc.).
   - Create calculated fields (e.g., percentages for each severity level) and group data (e.g., Cars = Car + Taxi).

4. **Visual Engineering:**  
   - Create visualizations:
     - **Donut Charts:** (70% inner radius, external labels)
     - **Line Charts:** Compare monthly trends (2021 vs. 2022)
     - **Treemaps:** Visualize accident distribution by road surface
   - Assemble these into an interactive dashboard using slicers and timelines.

---

## Dashboard Structure

The workbook includes the following sheets:

- **Dashboard:** Main interactive interface with slicers, timelines, and drill-down features.


https://github.com/user-attachments/assets/36c253d6-41f1-4b2f-b59f-081e972051a8


- **KPI:** PivotTables displaying core metrics.
- ![KPI](https://github.com/user-attachments/assets/e4cf04fc-b9dc-4f8e-b679-6bf8c4e2184c)

- **Monthly Trend:** Line chart comparing accident trends between 2021 and 2022.
- ![Monthly Trend](https://github.com/user-attachments/assets/f691355f-7312-4d78-b8c3-65073abdd3ca)

- **Road Type:** Analysis by road type.
- ![Road Type](https://github.com/user-attachments/assets/7951c8f8-e9be-4be8-a05f-646f245bd8ac)

- **Tree Map:** Visual representation of accident data by road surface.
- ![Tree Map](https://github.com/user-attachments/assets/34d17442-47cc-4a35-a517-1ec8a0a29e31)

- **Donut Charts:** Proportional breakdown of accident severity.
- ![Donut Charts](https://github.com/user-attachments/assets/506b0a10-db43-44a3-85c4-756a745e1826)

- **Data Analysis Sheet:** Detailed view of PivotTables and calculated fields.
- ![Data Analysis Sheet](https://github.com/user-attachments/assets/ee25aba6-8042-43c1-81f5-1344d5df4a43)

- **Data Sheet:** Original raw dataset.
- ![Data Sheet](https://github.com/user-attachments/assets/b4947b52-df98-4df5-9c0b-20c7fdb9efdd)


---

## How to Use

1. **Download the Repository:**  
   Clone or download the repository to your local machine.
2. **Open the Excel File:**  
   Open<a href="https://github.com/Younes-Sehanine/Road_Accident_Dashboard/blob/main/Road_Accident_Dashboard.xlsx" >`Road_Accident_Dashboard.xlsx`</a> using Office 365.
3. **Interact with the Dashboard:**  
   Start with the **Dashboard** sheet to use dynamic slicers and timelines, then explore individual sheets for deeper insights.
4. **Learn More:**  
   Visit my website for a detailed walkthrough of the methodology and design choices.

---

## Announcement & Thanks

###Thank you for reviewing this project. For additional information and to explore more of my work, please visit my [portfolio website](https://yourportfolio.example.com) and find further details about this project at [Project Link](https://yourprojectlink.example.com). I also extend my sincere thanks to Swapnjeet S from Data Tutorials for his invaluable YouTube tutorials that played a key role in this project's development.
