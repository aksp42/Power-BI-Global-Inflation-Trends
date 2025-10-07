📊 Global Inflation Risk Analysis Dashboard
🧠 Project Overview

This project is a comprehensive Data Analysis solution developed in Microsoft Power BI to analyze global inflation rates (1980–2024).
The primary goal is to transform complex, wide-format macroeconomic data into an actionable, multi-page dashboard that delivers strategic insights into volatility, geographic risk concentration, and the verified performance of a key risk mitigation mechanism.

❗ The Problem

Global inflation data is often unstructured and highly volatile, making it difficult for stakeholders to gauge financial risk or measure the effectiveness of hedging policies.
This project addresses the lack of a unified, quantifiable system to assess policy efficacy and residual risk concentration.

🚀 Solution: Key Metrics & Dashboard Structure

The solution is an interactive four-page Power BI dashboard focused on two core KPIs:

Adjustment Effectiveness (%)

Residual Risk Disparity (%)

📑 Dashboard Pages

Strategic Summary – High-level trends and overall mechanism performance.

Operational Risk Hotspots – Geographic and seasonal volatility analysis.

Mechanism Effectiveness – Comparison of Raw Rate vs Adjusted Rate for KPI validation.

Deep Dive Analysis – Exploration of outliers and disparity across risk categories.

🎯 Key Findings & Project Success
Finding Category	Key Insight	Data Point
Policy Success Rate	The implemented mechanism reduced maximum inflation exposure.	Adjustment Effectiveness: 90.00%
Residual Risk	Large disparity between highest and lowest risk categories.	Residual Risk Disparity: 33,203.18%
Top Hotspot	Risk is highly concentrated, with one country contributing more than half of the total rate.	Armenia contributed 51.63% of analyzed inflation sum.
Temporal Risk	Volatility follows a predictable pattern with a high-risk window.	Volatility peaks in October.
🛠️ Technical Stack & Methodology
Component	Tool / Language	Purpose
Data Visualization	Microsoft Power BI	Dashboard creation and reporting
Data Transformation	Power Query (M-Language)	Cleaning, unpivoting, and modeling
Business Logic / KPIs	DAX (Data Analysis Expressions)	Calculation of metrics and KPIs
Data Source	global_inflation_data.csv	Raw time-series dataset (1980–2024)
📁 Repository Structure
├── global_inflation_data.csv           # Raw dataset  
├── Global_Inflation_Risk_Analysis.pbix # Power BI dashboard file  
├── Final_Project_Report.md             # Official documentation  
└── Screenshots/                        # Dashboard visuals

🔮 Future Scope

To enhance the project’s predictive and analytical capabilities:

ML Integration: Add models like ARIMA or Prophet for 12–24 month forecasting.

External Variables: Include commodity prices and interest rates to assess correlation.

Advanced Navigation: Enable dynamic drill-through for country-specific risk exploration.

💻 Usage Instructions

Download the repository content.

Install Microsoft Power BI Desktop.

Open the Global_Inflation_Risk_Analysis.pbix file.

Use slicers and filters to interact with the data by country, year, and risk category.

⭐ If you find this project insightful, feel free to star the repository and explore the dashboard visuals!
