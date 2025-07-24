# Zillow U.S. Real Estate & Affordability Analysis

### [View the Live Interactive Dashboard on Tableau Public] https://public.tableau.com/app/profile/sam.rogers4571/viz/U_S_HousingAffordabilityAnalysis_17533872927120/U_S_HousingAffordabilityDashboard?publish=yes

## Project Overview
This project is a comprehensive analysis of the U.S. housing market using Zillow's historical data, supplemented with national median income data. The analysis begins with a deep data exploration and modeling in a multi-sheet Excel workbook and culminates in an interactive affordability dashboard built in Tableau. The goal is to transform raw housing data into actionable insights about market performance, risk, and affordability.

## Project Components

### 1. Excel Analytical Model (`Zillow_Housing_Analysis.xlsx`)
This workbook contains the core data and a series of dynamic dashboards:

* **`Stats`**: Calculates over 20 dynamic performance and risk metrics (CAGR, Max Drawdown, Sharpe Ratio, etc.) for any selected U.S. metro and includes a head-to-head comparison feature.
* **`Affordability Snapshot`**: A summary dashboard that calculates the "Affordability Gap"—the income required to afford a median-priced home—and ranks the most and least affordable markets in the U.S.
* **`Affordability Index`**: A detailed data table and chart showing the home price-to-income ratio over time for a selected metro against a fixed affordability benchmark.
* **`Scenario`**: An interactive mortgage calculator to model monthly payments and required income based on changing assumptions for home price, interest rate, and down payment.
* **`Forecast`**: A predictive model that forecasts future home prices for 12 months and visualizes it against the full historical data.
* **`Market Movers`**: A dashboard to instantly find the Top 5 and Bottom 5 most expensive housing markets based on their current home values.
* **`AllZHV` & `IncomeData`**: The cleaned and prepared source data sheets.

### 2. Tableau Affordability Dashboard (Linked Above)
An interactive dashboard published to Tableau Public that visualizes the core insight from the project:

* Integrates Zillow home price data with national median household income data.
* Visualizes the "Home Price-to-Income" ratio over time against a fixed affordability benchmark.
* Features an interactive filter to explore the affordability trend for any specific U.S. metro.

## Key Skills Demonstrated
* **Data Cleaning & Preparation (ETL)**: Creating clean data sources for analysis in both Excel and Tableau.
* **Advanced Excel Formulas**: Utilizing dynamic array formulas, legacy array formulas (`Ctrl+Shift+Enter`), `LET`, `XLOOKUP`, `FILTER`, `SUMIFS`, and `INDEX/MATCH`.
* **Financial Modeling**: Building interactive scenario analysis tools with `What-If Analysis`.
* **Data Integration**: Joining Zillow housing data with external `Median Income` data to create a derived metric.
* **KPI Development**: Engineering key metrics like the Affordability Ratio and Affordability Gap.
* **Dashboarding & Visualization**: Creating multiple dynamic dashboards in Excel and a final, interactive dashboard in Tableau.
* **Time-Series Analysis & Forecasting**: Using Excel's forecasting tools to predict future trends.
