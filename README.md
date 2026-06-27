# HR Attrition Analysis & Prediction

**Tools:** Excel · Python · SPSS Modeler · Tableau  
**Dataset:** IBM HR Analytics Employee Attrition (Kaggle)  
**Domain:** People Analytics | HR Intelligence

## Live Dashboard
[View Interactive Tableau Dashboard](https://public.tableau.com/app/profile/muskan.choudhary8375/viz/HRAttritionAnalysisDashboard_17825895443370/HRAttritionAnalysisDashboard)

## Project Overview
Analyzed IBM HR dataset of 1,470 employees to identify key drivers 
of employee attrition and built a predictive model using SPSS Modeler 
with 91.84% accuracy.

## Key Findings
- Overall attrition rate is 16.1%, above industry average of 10-12%
- Sales Representatives have 39.8% attrition — highest of all roles
- Overtime workers quit at 3x the rate of non-overtime workers
- Employees who left earned significantly less across all age groups
- Single employees leave at 25% vs 12% for married employees
- TotalWorkingYears is the strongest predictor of attrition

## SPSS Prediction Model
- Algorithm: C5.0 Decision Tree
- Accuracy: 91.84% (1,350/1,470 correct predictions)
- Top predictors: TotalWorkingYears, MaritalStatus, JobLevel
- Tree depth: 9 levels

## Business Recommendations
- Eliminate or compensate mandatory overtime immediately
- Create targeted retention program for Sales Representatives
- Review salary bands for junior employees and Lab Technicians
- Introduce flexible work arrangements for employees living far from office
- Fast track promotions for high performers in at-risk roles

## Repository Structure
- `excel/` — Pivot table analysis and charts
- `notebook/` — Python EDA and correlation analysis
- `spss/` — Predictive model screenshots and results
- `tableau/` — Dashboard screenshots

## Data Source
IBM HR Analytics Employee Attrition Dataset  
Download: https://www.kaggle.com/datasets/pavansubhasht/ibm-hr-analytics-attrition-dataset
