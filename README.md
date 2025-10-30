# 💼 Executive_Investment_Insights_Dashboard  
**Data Source:** Financial Data — Cleaned in **MySQL**, Visualized in **Power BI**

## 📊 Project Overview  
This Power BI project analyzes **investor behavior and financial preferences** to reveal how individuals allocate their funds across different investment avenues.  
The dataset was **cleaned and transformed in MySQL**, then visualized in **Microsoft Power BI** using DAX measures, KPIs, and interactive visuals.  

The dashboard provides actionable insights into:  
- Gender and age-based investment behavior  
- Most preferred investment avenues  
- Expected returns and risk expectations  
- Investment duration and monitoring frequency  

## 🎯 Project Objectives  
- Identify investor demographics with the **highest investment participation**  
- Measure **average investment distribution** across key avenues (Mutual Funds, Gold, Bonds, etc.)  
- Analyze **expected returns and investment durations**  
- Create **interactive visuals** that allow executives to explore investment trends dynamically  

## ⚙️ Tools & Technologies  
| Category | Tools Used |
|-----------|-------------|
| Data Preparation | MySQL, Excel |
| Data Visualization | Microsoft Power BI |
| Data Cleaning | SQL Queries (Joins, Aggregations, Group By) |
| Documentation | Markdown (GitHub README), Excel metadata tracking |

## 🧩 Workflow Overview  
1. **Data Extraction:**  
   - Imported investor dataset (`Financial_Data.csv`) into **MySQL**.  
   - Reviewed for nulls, inconsistencies, and incorrect data types.  

2. **Data Cleaning:**  
   - Normalized column names and handled missing values.  
   - Aggregated investment totals by gender, age, and objective.  
   - Used SQL queries to calculate key metrics (Average Investment, Total Investors, etc.).  

3. **Data Modeling:**  
   - Exported the cleaned data into Power BI.  
   - Created **relationships** between demographic and investment tables.  
   - Built DAX measures for KPIs such as:  

     **DAX**
     Total Investors = COUNT(finance_data[Gender])
     Average Investment = AVERAGE(finance_data[Mutual_Funds])
     Total Mutual Funds = SUM(finance_data[Mutual_Funds])
     Total Gold = SUM(finance_data[Gold])

4. **Dashboard Design:**  
   - Designed an executive-style layout across **three pages**:  
     - **Page 1:** KPI Overview (Average Investment, Total Investors, Gender Analysis)  
     - **Page 2:** Executive Investment Overview (Investment Objectives, Returns, Duration)  
     - **Page 3:** Interactive Insights (Slicers for Gender, Age, and Purpose)  

## 📸 Dashboard Narratives  
The dashboard highlights three main dimensions of investor behavior:  
1️⃣ **Average Investment by Demographics**  
   - Male and female investors show similar engagement, though women invest more in stable avenues like Bonds and PPF.  
2️⃣ **Preferred Investment Avenues**  
   - Mutual Funds and Equity Markets dominate investment patterns, followed by Fixed Deposits and Gold.  
3️⃣ **Expected Returns (%)**  
   - Most investors expect returns between **10–15%**, reflecting moderate risk appetite.  
4️⃣ **Investment Duration**  
   - Majority of investors plan for **long-term growth**, aligning with wealth accumulation objectives.  
5️⃣ **Objective Distribution**  
   - Key motives include wealth creation, children’s education, and retirement planning.  
6️⃣ **Interactive Slicers (Right Panel)**  
   - Users can filter by Gender, Age, and Objective to dynamically explore patterns.  

## 💡 Key Insights  
- **Mutual Funds (38%)** and **Equity Markets (26%)** are the top investment choices.  
- Female investors exhibit **higher average investment per avenue** than males.  
- **Long-term objectives (5+ years)** dominate investment behavior.  
- **Stable return expectations (10–15%)** suggest balanced risk preferences.  
- Majority of investors actively **monitor investments monthly or quarterly**.  

## 🧠 Learning Outcomes  
This project strengthened my ability to:  
- Clean and transform financial datasets using **MySQL** queries.  
- Develop and format **executive dashboards** in **Power BI**.  
- Create **DAX measures** and KPIs to track key metrics.  
- Apply **data storytelling** techniques for professional business insights.
- 
## 📸 Dashboard Preview  
<img width="939" height="459" alt="image" src="https://github.com/user-attachments/assets/3a54bdf0-594d-4cd1-ba06-7b38ebcf2e97" />

## 🧾 Project Files  
| File | Description |
|------|--------------|
| `financial_data_queries.sql` | SQL queries used for cleaning and aggregation |
| `Financial_Data.csv` | Processed dataset ready for Power BI |
| `Executive_Investment_Insights.pbix` | Power BI dashboard file |
| `images/executive_investment_dashboard.png` | Screenshot of the dashboard |
| `README.md` | Full project documentation |

## 💰 Relevance to Finance & Analytics Roles  
This project demonstrates:  
- Expertise in **financial analytics**, **data modeling**, and **KPI reporting**  
- Proficiency in **MySQL** for data cleaning and **Power BI** for visualization  
- Strong storytelling and dashboard design skills  
- Ability to translate financial data into **executive-level business insights**

## 📚 Author  
👩🏽‍💻 **U Dekontee Kun**  
📬 Email: udekontee@gmail.com  
🔗 Portfolio: [github.com/udekontee](https://github.com/udekontee)
