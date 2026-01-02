

## 📊 Project Overview
This project provides a comprehensive visualization of global food production trends across different countries, years, and crop categories. The dashboard is designed to analyze agricultural productivity, identifying the world's leading food producers and tracking the shift in crop yields over time to support discussions on global food security and supply chain stability.

## 🚀 Key Performance Indicators (KPIs)
The dashboard tracks vital agricultural metrics:
* **Total Production:** Cumulative weight (tonnes) of food produced globally.
* **Yield per Hectare:** Efficiency metric measuring agricultural productivity.
* **Top Producing Countries:** Ranking of nations by total agricultural output.
* **Crop Diversity Index:** Variety of crops produced within specific regions.
* **Year-over-Year (YoY) Growth:** Percentage change in production volume annually.

## 🛠️ Technical Implementation
### Data Transformation (Power Query)
* **Dataset Normalization:** Cleaned complex datasets from sources like the FAO (Food and Agriculture Organization), handling variations in units (kg vs. tonnes) and inconsistent country naming conventions.
* **Pivoting & Unpivoting:** Transformed wide-format agricultural data into a long-format structure suitable for time-series analysis.
* **Data Filtering:** Removed outliers and handled null values in historical records to ensure trend accuracy.

### Data Modeling & DAX
* **DAX Measures:** Created advanced measures for **Total Yield**, **Regional Contribution %**, and **Moving Averages** to smooth out seasonal fluctuations.
* **Star Schema:** Developed a lean data model connecting a central Fact table (Production) to Dimension tables for Geography, Crop Type, and Time.

## 📈 Dashboard Highlights
* **Global Production Map:** A choropleth map visualizing food production intensity by country.
* **Crop Category Breakdown:** A treemap or pie chart showing the dominance of Cereals, Fruits, Vegetables, and Oilcrops.
* **Historical Growth Trend:** A line chart depicting the trajectory of food production from the late 20th century to the present.
* **Efficiency Analysis:** A scatter plot comparing "Land Use" vs. "Production Output" to identify high-efficiency regions.

## 💡 Business & Environmental Insights
* **Regional Dominance:** Identified that a small group of countries (e.g., China, USA, India) accounts for over 50% of certain staple crop productions, highlighting potential risks in global supply chains.
* **Sustainability Trends:** Analysis of yield per hectare shows that while total production is increasing, the rate of efficiency growth is slowing in certain "breadbasket" regions.
* **Crop Shift:** Observed a significant increase in the production of oilcrops and cash crops compared to traditional grains over the last decade.

## 📂 Repository Structure
```text
├── Data/                   # Agricultural datasets (CSV/Excel)
├── Dashboard/              # Food_Production_Analysis.pbix
├── Screenshots/            # Images of the Power BI interface
└── README.md               # Project documentation# Global-Food-Production-Trends-and-Analysis-A-Comprehensive-Study-from-1961-to-2023
