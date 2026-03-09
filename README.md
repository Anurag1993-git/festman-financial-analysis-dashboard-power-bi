# festman-financial-analysis-dashboard-power-bi
_The analysis identified revenue trends, key revenue-generating segments, major cost drivers, and profitability patterns to support better financial decision-making_

---

<h2><a class="anchor" id="project overview"></a>Project Overview</h2>

The Festman Financial Analysis Dashboard is a data analytics project that focuses on analyzing a company’s financial data to evaluate revenue, expenses, and profitability trends. The project involves cleaning and transforming financial datasets and building an interactive dashboard in Power BI to visualize key financial KPIs. The dashboard enables users to track financial performance, identify cost drivers, and gain insights that support data-driven financial planning and business decision-making.

---
<h2><a class="anchor" id="business-problem"></a>Business Problem</h2>

Organizations often manage financial data across multiple spreadsheets and systems, making it difficult to gain a clear view of overall financial performance. This lack of centralized visibility makes it challenging to track revenue, expenses, and profitability trends, identify cost drivers, and support timely decision-making. The Festman Financial Analysis Dashboard addresses this problem by consolidating financial data into an interactive dashboard that enables stakeholders to monitor key financial KPIs and analyze financial performance efficiently

---
<h2><a class="anchor" id="dataset"></a>Dataset</h2>

- Multiple CSV files located in `/Dataset/` folder (segment, countries, products, etc)
- Summary tables are created from segment and products for analysis

---

<h2><a class="anchor" id="tools--technologies"></a>Tools & Technologies</h2>

- Microsoft Excel – Data cleaning, preprocessing, and initial exploration
- Power BI – Interactive dashboard development and data visualization
- Power Query – Data transformation and data modeling
- DAX (Data Analysis Expressions) – Creating calculated measures and financial KPIs
- GitHub

---

<h2><a class="anchor" id="project-structure"></a>Project Structure</h2>

```
FestMan - Financial Analysis Dashboard 
│
├── README.md
├── .gitignore
├── requirements.txt
├── dashboard/                  # Power BI dashboard file
│   └── festman-financial-analysis-dashboard
```
---
<h2><a class="anchor" id="data-cleaning--preparation"></a>Data Cleaning & Preparation</h2>

The financial dataset was cleaned and prepared to:
- Ensure accurate analysis and reliable dashboard insights
- Missing values, duplicate records, and inconsistent data formats were identified and corrected
- Data types such as dates, numerical values, and categories were standardized
- Calculated fields like profit and profit margin were created
- The cleaned dataset was then transformed using Power Query and Excel to make it suitable for analysis and visualization in Power BI

---
<h2><a class="anchor" id="exploratory-data-analysis-eda"></a>Exploratory Data Analysis (EDA)</h2>

Exploratory Data Analysis was performed to understand the structure and patterns within the financial dataset. the following insights were identified:

**Revenue Trends**
- Certain months showed higher revenue, indicating possible seasonal or demand-driven patterns.
**Expense distribution**
- A few categories contributed to a large portion of total expenses, highlighting major cost drivers.
**Profitability patterns**
- Profit varied across time periods, showing that higher revenue did not always guarantee higher profit due to increased expenses.
**Top-performing segments**
- Some business segments or categories generated significantly higher revenue compared to others.
**Financial fluctuations**
- Variations in revenue and expenses over time revealed areas where financial performance could be optimized.

---
<h2><a class="anchor" id="research-questions--key-findings"></a>Research Questions & Key Findings</h2>

1. What are the overall revenue, expenses, and profit trends over time?
2. Which categories or segments generate the highest revenue?
3. What are the major cost drivers contributing to total expenses?
4. How does profitability vary across different periods or categories?
5. Which areas of the business show opportunities for improving financial performance?

📊 Key Findings
- Revenue shows noticeable variations across different time periods, indicating possible seasonal trends
- A small number of categories contribute to a large share of total revenue, highlighting key revenue drivers.
- Certain expense categories represent the major portion of operational costs.
- Profitability fluctuates because higher revenue periods also sometimes involve higher expenses.
- Identifying these patterns helps stakeholders optimize costs and improve financial planning.

---
<h2><a class="anchor" id="dashboard"></a>Dashboard</h2>

- Power BI dashboard shows:
  - Financial KPI's
  - Revenue Analysis
  - Expense Analysis
  - Profitability Insights
  - Interactive Insights

 ![Live Dashboard](images/dashboard.png)

---
<h2><a class="anchor" id="how-to-run-this-project"></a>How to Run This Project</h2>

1. Download the project files from GitHub.
2. Install Microsoft Power BI Desktop.
3. Open the Festman_Financial_Dashboard.pbix file.
4. If prompted, update the dataset path to Festman_Financial_Dataset.csv.
5. Click Refresh to load the data.
6. Explore the interactive financial dashboard.

---
<h2><a class="anchor" id="final-recommendations"></a>Final Recommendations</h2>

- Focus on High-Revenue Regions
- Improve Low-Performing Product Categories
- Optimize Cost Management
- Leverage Seasonal Sales Trends
- Strengthen Customer Retention Strategies

<h2><a class="anchor" id="author--contact"></a>Author & Contact</h2>

**Anurag Kaushik**

Data Analyst

📧 Email: anuragkdataanalyst@gmail.com  
🔗 [LinkedIn](https://www.linkedin.com/in/anuragkdatainsights/)  
🔗 [Portfolio](https://www.canva.com/design/)



