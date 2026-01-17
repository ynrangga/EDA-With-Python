# Garment Employee Productivity Analysis using Python (EDA & Visualization)

## 📌 Project Overview
Exploratory data analysis project using Python to analyze garment employee productivity. Focuses on workforce efficiency, overtime impact, and operational factors through statistical visualization.

## 🎯 Objectives
- Analyze productivity patterns of garment industry employees
- Identify key factors affecting actual productivity
- Explore correlations between operational variables
- Generate data-driven insights to support managerial decision-making

## 📂 Dataset Information
- Dataset: Productivity Prediction of Garment Employees
- Target Variable: actual_productivity
- Total Features: 15
- Data Type: Numerical & Categorical
- Domain: Manufacturing Analytics / HR Analytics
### Key Features:
- Workload & efficiency: smv, wip, over_time
- Workforce metrics: no_of_workers, idle_time, idle_men
- Performance indicators: targeted_productivity, actual_productivity
- Contextual features: department, day, quarter, team

## 🛠 Tools & Technologies
- Python
- Google Colab
- pandas, numpy
- matplotlib, seaborn

## 🔍 Key Insights
- Several variables (wip, idle_time, incentive) show highly right-skewed distributions
- targeted_productivity remains consistently high across observations
- Strong positive correlation between:
  - smv and no_of_workers (≈ 0.91)
  - smv and over_time (≈ 0.67)
- Overtime shows a weak but positive relationship with productivity, varying by department
- Sewing department exhibits higher overtime intensity compared to finishing
