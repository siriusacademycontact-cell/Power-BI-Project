# 🚦 Road Accident Dashboard

An interactive Business Intelligence dashboard that analyzes road accident data, providing insights into casualty severity, vehicle types, road conditions, and accident trends over time.

![Dashboard Preview](dashboard_preview.png)

## 📊 Overview

This dashboard offers a comprehensive view of road accident statistics, helping stakeholders (traffic authorities, insurance companies, city planners) identify patterns and high-risk factors contributing to road accidents.

**Total Casualties Analyzed:** 417,883

## ✨ Key Features

- **Casualty Severity Breakdown** — Fatal, Serious, and Slight casualties with percentage share
- **Vehicle-wise Casualty Analysis** — Breakdown by Car, Bus, Van, Cycle, Agricultural Vehicle, and others
- **Yearly Trend Comparison** — Current Year (CY) vs Previous Year (PY) casualties across all 12 months
- **Road Type Analysis** — Casualties segmented by Single Carriageway, Dual Carriageway, Roundabout, One-way Street, and Slip Road
- **Road Surface Conditions** — Comparison of accidents on Dry vs Wet/Icy/Snow surfaces
- **Location Insights** — Urban vs Rural casualty distribution
- **Light Condition Analysis** — Daylight vs Dark accident occurrences
- **Interactive Filters** — Filter by Accident Date (quarterly) and Urban/Rural classification

## 📈 Key Metrics

| Metric | Value | % of Total |
|---|---|---|
| Fatal Casualties | 7,135 | 1.7% |
| Serious Casualties | 59,312 | 14.2% |
| Slight Casualties | 351,436 | 84.1% |
| Casualties by Car | 333,485 | 79.3% |

## 🚗 Casualties by Vehicle Type

| Vehicle Type | Casualties |
|---|---|
| Car | 333,485 |
| Van | 33,472 |
| Cycle | 23,466 |
| Bus | 12,798 |
| Agricultural Vehicle | 1,032 |
| Other | 3,424 |

## 🛠️ Tools & Technologies

- **Power BI** — Dashboard design and data visualization *(update if using Tableau, Excel, or another tool)*
- **Data Modeling** — Relationships between accident, vehicle, and casualty tables
- **DAX / Calculated Measures** — For KPI cards and dynamic percentages
- **Data Source** — Road accident dataset *(add source link/name here)*

## 📂 Project Structure

```
road-accident-dashboard/
│
├── dashboard.pbix              # Power BI dashboard file
├── data/
│   └── road_accidents.csv      # Raw/cleaned dataset
├── images/
│   └── dashboard_preview.png   # Dashboard screenshot
└── README.md
```

## 🚀 How to Use

1. Clone this repository
   ```bash
   git clone https://github.com/<your-username>/road-accident-dashboard.git
   ```
2. Open `dashboard.pbix` in Power BI Desktop (or the relevant tool)
3. Refresh the data source if needed
4. Explore the dashboard using the filter panel (Accident Date, Urban/Rural)

## 🔍 Insights

- The majority of casualties (**84.1%**) fall under the **Slight** severity category, while fatal casualties account for a smaller but critical **1.7%**.
- **Cars** are involved in the highest share of casualties at **79.3%**, followed by Vans and Cycles.
- **Single carriageways** account for the highest number of casualties (309.7K) compared to other road types.
- Casualties occur more frequently in **Rural** areas (255.9K) compared to Urban areas (162.0K).
- Most accidents happen during **Daylight** (305.0K) rather than Dark conditions (112.9K).
- **Dry road surfaces** are associated with significantly more casualties than Wet/Ice/Snow conditions — likely reflecting overall driving exposure/volume in dry conditions.

## 📌 Future Improvements

- Add predictive analytics (e.g., forecasting high-risk periods)
- Integrate geospatial mapping for accident hotspots
- Add driver demographic analysis (age, experience, gender)
- Automate data refresh via scheduled pipeline

## 👤 Author

**[Your Name]**
📧 [your.email@example.com]
🔗 [LinkedIn](https://linkedin.com/in/your-profile) | [Portfolio](https://your-portfolio.com)

## 📄 License

This project is licensed under the MIT License — feel free to use and adapt it.
