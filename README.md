📊 Global Inflation Risk Analysis Dashboard

Project Overview
This project is a comprehensive Data Analysis solution developed in Microsoft Power BI to analyze global inflation rates from 1980 to 2024. The primary goal is to transform complex, wide-format macroeconomic data into an actionable, multi-page dashboard that provides strategic insights into volatility, geographic risk concentration, and the verifiable performance of a key risk mitigation mechanism.

The Problem
Global inflation data is often unstructured and highly volatile, making it difficult for stakeholders to accurately gauge financial risk and the effectiveness of risk-hedging policies. This project addresses the lack of a unified, quantifiable system to measure policy efficacy and residual risk concentration.

🚀 Solution: Key Metrics & Dashboard Structure
The solution is an interactive, four-page Power BI dashboard centered around measuring two critical KPIs: Adjustment Effectiveness and Residual Risk Disparity.

Dashboard Pages
Strategic Summary: High-level trends and overall mechanism performance.

Operational Risk Hotspots: Geographic and seasonal volatility analysis.

Mechanism Effectiveness: Detailed comparison of Raw Rate versus Adjusted Rate for KPI validation.

Deep Dive Analysis: Focus on extreme outliers and risk category disparity.

🎯 Key Findings & Project Success
The analysis across the four dashboard pages led to three major, data-backed conclusions:

Finding Category

Key Insight

Data Point

Policy Success Rate

The implemented risk mitigation mechanism successfully reduced maximum inflation exposure.

Adjustment Effectiveness: 90.00%

Residual Risk

An alarming disparity exists between the highest and lowest risk categories, emphasizing the extreme impact of outliers.

Residual Risk Disparity: 33,203.18%

Top Hotspot

Risk is highly concentrated, with one country contributing more than half of the total rate in the analyzed subset.

Armenia contributed 51.63% of the analyzed inflation sum.

Temporal Risk

Volatility follows a predictable annual pattern, indicating a specific high-risk window for proactive measures.

Volatility consistently peaks in October.

🛠️ Technical Stack & Methodology
Component

Tool/Language

Purpose

Data Visualization

Microsoft Power BI

Dashboard creation, reporting, and interaction.

Data Transformation

Power Query (M-Language)

Data cleaning, unpivoting of time-series data, and initial modeling.

Business Logic/KPIs

DAX (Data Analysis Expressions)

Calculation of core metrics such as Adjusted Rate, Risk Category, Adjustment Effectiveness (%), and Risk Disparity (%).

Data Source

global_inflation_data.csv

Raw time-series data for multiple countries (1980–2024).

📁 Repository Structure
global_inflation_data.csv: The raw dataset used for analysis.

Global_Inflation_Risk_Analysis.pbix: The complete, interactive Power BI report file.

Final_Project_Report.md: The official project documentation.

Screenshots/: Folder containing dashboard page visuals for demonstration.

🚀 Future Scope
To enhance the project's predictive power and decision-making capabilities:

ML Integration: Implement Machine Learning models (e.g., ARIMA or Prophet) for 12−24 month inflation forecasting.

External Variables: Integrate data on Commodity Prices and Interest Rates to determine correlation with inflation spikes.

Advanced Navigation: Implement dynamic drill-through functionality for deeper, country-specific analysis.

💻 Usage
To view and interact with the full analysis:

Download the repository content.

Ensure you have Microsoft Power BI Desktop installed.

Open the Global_Inflation_Risk_Analysis.pbix file.

Interact with the slicers and filters to explore data by country, year, and risk category.
