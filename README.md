# Investment-Behavior-Dashboard-Power-BI-
Power BI dashboard analyzing investor behavior, preferences, and expected returns using DAX measures, KPIs, and interactive visuals to uncover key financial insights. 
Tags: Power BI, data analytics, business intelligence, finance, data visualization, dax, dashboard, portfolio-project

# 🎯 Project Overview
The **Investment Behavior Dashboard** explores investor preferences, objectives, and expected returns through data visualization in **Microsoft Power BI**.  
It highlights behavioral patterns by gender, age, duration, and investment type, helping financial analysts identify where investors allocate their funds and what motivates their decisions.

## 📁 Dataset Information
- **File:** Finance_Data.csv  
- **Records:** ~1,000 investor profiles  
- **Source:** Sample dataset (data.gov / open financial data)  
- **Key Columns:**
  - Demographics: `Gender`, `Age`
  - Investment Types: `Mutual_Funds`, `Equity_Market`, `Government_Bonds`, `Fixed_Deposits`, `Gold`, `PPF`, `Debentures`, `Stock_Marktet`
  - Objectives: `Objective`, `Purpose`, `Expect`, `Duration`, `Invest_Monitor`

---

## 🧮 Tools & Techniques
- **Tool Used:** Microsoft Power BI Desktop  
- **Techniques:** Data cleaning, DAX measures, KPI creation, visualization, and storytelling.  
- **Skills Demonstrated:**
  - Power BI modeling and DAX calculations  
  - KPI development and layout design  
  - Data storytelling with business context  
  - Executive dashboard formatting  

---

## 🧠 Key DAX Measures
```DAX
Average Investment = AVERAGE(finance_data[Mutual_Funds])
Total Investors = COUNT(finance_data[gender])
Total Mutual Funds = SUM(finance_data[Mutual_Funds])
Total Equity Market = SUM(finance_data[Equity_Market])
Total Debentures = SUM(finance_data[Debentures])
Total Government Bonds = SUM(finance_data[Government_Bonds])
Total Fixed Deposits = SUM(finance_data[Fixed_Deposits])
Total PPF = SUM(finance_data[PPF])
Total Gold = SUM(finance_data[Gold])
Total Stock Market = SUM(finance_data[Stock_Marktet])
Objective % =
DIVIDE(
    COUNT(finance_data[Objective]),
    CALCULATE(COUNT(finance_data[Objective]), ALL(finance_data[Objective]))
)

## 🧩 Dashboard Structure
### Page 1: KPI Overview
- Average Investment  
- Total Investors  
- Average Investment by Age Group  
- Average Investment by Gender  

### Page 2: Executive Investment Overview
- Preferred Investment Avenues  
- Investment Objectives Distribution  
- Expected Investment Returns (%)  
- Investment Duration Trend  
![Uploading image.png…]()

### Page 3: Interactive Insights
- Gender and Age Slicers  
- Decomposition Tree for deeper diagnostics  
- Drillthrough to investor profiles  

---

## 📊 Visuals Used
| Visual Type | Description | Purpose |
|--------------|--------------|----------|
| **Card (KPI)** | Shows summary metrics | Average Investment, Total Investors |
| **Bar Chart** | Compares total investments across avenues | Mutual Funds, Equity, Bonds, etc. |
| **Treemap** | Shows objective distribution | Investment Objectives |
| **Column Chart** | Displays duration trend | Duration (Short vs Long Term) |
| **Line Chart** | Shows average investment by age | Age group trend |
| **Pie Chart** | Displays expected return ranges | Expect column |
| **Slicers** | Adds interactivity | Gender, Age, Objective |

