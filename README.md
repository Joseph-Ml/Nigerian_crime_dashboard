Repository: Nigeria-Crime-Analysis
🔎 Project Overview

This project analyzes violent events and fatalities in Nigeria (2020–2024) using structured event data. The goal is to uncover regional, temporal, and typological patterns of violence and to build an interactive Power BI dashboard for monitoring conflict dynamics.

By combining data cleaning, exploratory data analysis (EDA) and KPI design, the project provides actionable insights for researchers, policymakers, and security analysts.

📊 Key Insights

Total Violent Events: 18.29k

Total Fatalities: 39k

Regional Trends:

North East: 14k fatalities (36.6% of total)

North West: 13k fatalities (32.2% of total)

South West: 2k fatalities (5.5% of total, lowest)

Temporal Trends:

January = most violent month (1,871 events)

April = least violent month (1,396 events)

Event Type Trends: Political violence dominates (74.66% of all events)

State-Level Patterns:

Borno = highest fatalities (12,129)

Zamfara = second (4,443)

Yearly Patterns:

2021 = deadliest year (10,880 fatalities)

2022 = second (10,754 fatalities)

2024 = lowest in dataset (532 fatalities, partial data)

⚙️ Methodology

Data Cleaning

Removed duplicates, handled missing values

Converted year → categorical (object)

Extracted event_date (without timestamp)

EDA

Trends by month and year

Distribution of fatalities by region/state

Event type frequencies

Power BI Dashboard

KPI Cards: Most Affected State, Most Common Event Type, Year with Highest Fatalities

Line & Column Trends: events vs fatalities

Donut/Stacked Charts: event types

Top 10 States: by fatalities

Interactive Slicer: year

Map Visuals: fatalities hotspots

📂 Repository Structure
Nigeria-Crime-Analysis/
│
├── data/
│   ├── Crime_data_Nigeria.xlsx     # Original dataset
│   ├── Cleaned_Crime_Data.xlsx     # Cleaned dataset for analysis
│
├── notebooks/
│   ├── EDA_Crime_Data.ipynb        # Python EDA notebook
│
├── dashboard/
│   ├── Nigeria_Crime_Dashboard.pbix # Power BI dashboard file
│
├── reports/
│   ├── Crime_Analysis_Report.pdf    # Analytical write-up (essay style)
│
├── README.md                       # Project overview & documentation

🚀 Tools & Technologies

Python (Pandas, Matplotlib, Seaborn, Plotly) → Data cleaning & EDA

Power BI → Interactive dashboard & KPIs

Excel → Data preparation and exploration

GitHub → Version control and project sharing

🎯 Purpose

This project contributes to the understanding of insecurity in Nigeria by:

Highlighting regional hotspots (Borno, Zamfara, etc.)

Showing seasonal/temporal patterns in violent events

Emphasizing the dominance of political violence in Nigeria’s conflict landscape

Providing a ready-to-use dashboard for researchers and policymakers

🧑‍💻 Author

Joseph Afunso

Library and Information Science student | Data Analyst | Researcher

Interested in conflict analysis, governance, and data-driven policymaking
