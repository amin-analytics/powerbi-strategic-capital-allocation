# Strategic Capital Allocation & Scenario Analysis (Power BI)
[![Live Dashboard](https://img.shields.io/badge/Live-Dashboard-blue)](https://bdcerts.com/projects/investment-simulator)

## Project Overview
This project simulates a real-world investment strategy use case using representative data. This project demonstrates advanced portfolio analytics and scenario modeling for capital allocation decisions in the renewable energy sector.
The dashboard evaluates how different investment strategies (Conservative, Balanced, Aggressive) impact portfolio performance under varying risk and cost assumptions.

The analysis is designed to support investment committees, strategy teams, and senior leadership in making risk-adjusted capital allocation decisions.

## 🔗 Live Interactive Dashboard

👉 **View Strategic Investment Decision Simulator**  
[https://bdcerts.com/projects/investment-simulator](https://bdcerts.com/projects/investment-simulator)

This scenario-based dashboard allows users to:
- Compare investment strategies (Aggressive / Balanced / Conservative)
- Analyze risk-adjusted IRR and CAPEX allocation
- Perform sensitivity analysis using what-if parameters

> Interactive Power BI visuals are embedded directly on the project page.

## Business Objectives
- Compare investment strategies on a risk-adjusted basis
- Quantify IRR sensitivity to risk premiums and CAPEX inflation
- Evaluate capital allocation efficiency across regions
- Identify whether higher-risk strategies outperform the base case

## Pages Included
### 1. Executive Strategy Overview
- Portfolio-level KPIs:
  - Risk-Adjusted IRR (%)
  - Total CAPEX Exposure (USD m)
  - IRR Change vs Base Case (%)
  - Portfolio Risk Index

- Strategy comparison: Conservative → Balanced → Aggressive
- Clear identification of base-case performance vs alternatives

### Key Insight:
- Higher-risk strategies do not necessarily generate superior risk-adjusted returns.

### 2. Scenario Sensitivity Analysis
- IRR sensitivity to:
  - Risk premium adjustments
  - CAPEX inflation scenarios
- Scenario-adjusted IRR vs Base Case comparison
- Visual separation between negative and improvement zones

### Key Insight:
- Aggressive strategies are more sensitive to downside assumptions than balanced or conservative approaches.

### 3. Capital Allocation & Recommendation
- CAPEX allocation by region and strategy
- Risk-adjusted performance comparison
- Strategy impact waterfall vs base case

### Key Insight:
- Balanced allocation minimizes downside while preserving portfolio returns, outperforming aggressive strategies on a risk-adjusted basis.

## Data Modeling & DAX
- Star schema with fact and dimension tables
- Static strategy dimension to enforce risk-based ordering
- Weighted IRR calculations
- Scenario-driven CAPEX and IRR adjustments
- Context-safe DAX using SELECTEDVALUE where applicable

## Tools & Skills Demonstrated
- Power BI (advanced modeling & visualization)
- DAX (scenario analysis, weighted metrics, sensitivity modeling)
- Portfolio analytics & investment logic
- Executive-level dashboard design
- Risk-adjusted performance evaluation

## Screenshots
Screenshots of all pages are included in the `screenshots` folder for quick review. A consolidated PDF containing all dashboard pages is also provided for convenience.

## 🔁 Direct Power BI Access (Optional)

If you prefer to open the report directly in Power BI Service:

🔗 https://app.powerbi.com/view?r=eyJrIjoiNGYwNzNmNzctYmE2OC00Yjg1LWExMzktYTJiN2ZmYTBlOGU1IiwidCI6IjJhMGRlOTE5LTRmNzUtNDhiYy1hMDJhLWUwMzRhMmM1MDgyMSIsImMiOjh9&pageName=2f004851a360e52ff492

## PBIX File Access
The Power BI (.pbix) file is available upon request for hiring managers and reviewers.

## Author
Amin  
Helsinki, Finland  
📧 amin@bdcerts.com

