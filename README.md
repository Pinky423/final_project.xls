📊 EXCEL CUSTOMER TRANSACTION ANALYSIS & DASHBOARD

📌 PROJECT OVERVIEW


This project is an Excel-based **Customer Transaction Analysis and Data Intelligence Dashboard**. It covers the complete workflow:

**Raw Data → Formula Analysis → Customer Analysis → Pivot Analysis → What-If Analysis → Regression → Lookup & Text Functions → Dashboard → Data Storytelling**

The project analyzes customer transactions, products, categories, regions, payment methods, customer segments, quantities, and total purchase amounts.

---

📂 WORKBOOK STRUCTURE


| Sheet | Purpose |
|---|---|
| **raw data** | Original customer transaction dataset |
| **Analysis** | Helper columns and formula-based analysis |
| **Customer analysis** | Customer purchase summary, ranking, and high-value customer identification |
| **pivot table** | Summary of quantity and unit price by year |
| **What-if analysis** | Scenario Manager and unit-price change analysis |
| **Regression** | Regression statistics and relationship analysis |
| **list compare** | List comparison, lookup, and text-function examples |
| **Visualization** | Visualization section for presenting analysis |
| **Dashboard** | Customer transaction KPIs and summary metrics |
| **Storytelling** | Main findings and business insights |


---

🧹 RAW DATA & DATA PREPARATION

The **raw data** sheet contains the original transaction records.

### Main Fields

- Transaction_ID
- Date
- Customer_ID
- Customer_Name
- Product_ID
- Product_Name
- Category
- Quantity
- Unit_Price
- Payment_Method
- Region
- Customer_Segment
- Customer_Since
- Total_Amount

The dataset contains **250 transaction records** and is used as the source for the analysis sheets.

---

🧮 FORMULA ANALYSIS & HELPER COLUMNS

The **Analysis** sheet extends the raw data with calculated helper columns.

 Helper Columns

- **Order_Month** – Extracts the month and year from the transaction date.
- **Month_End** – Finds the last date of the transaction month.
- **Customer_Tenure_Years** – Calculates customer tenure in years.
- **Timestamp** – Records the current date and time using a formula.
- **Name_Abbrev** – Creates initials from the customer name.

### Important Excel Functions

- `TEXT()` – Formats dates into month-year values.
- `EOMONTH()` – Returns the last date of a month.
- `DATEDIF()` – Calculates the difference between dates.
- `TODAY()` – Returns the current date.
- `NOW()` – Returns the current date and time.
- `LEFT()` – Extracts characters from the beginning of text.
- `RIGHT()` – Extracts characters from the end of text.
- `LEN()` – Counts the number of characters.
- `FIND()` – Finds the position of a character or space.
- `UPPER()` – Converts text into uppercase.

---

👥 CUSTOMER ANALYSIS

The **Customer analysis** sheet identifies customer purchase behavior and high-value customers.

### Main Analysis Fields

- Customer_ID
- Customer_Name
- Orders
- Units
- Total Purchase
- Rank
- High Value?
- Avg Order

### Main Calculations

- **Orders** – Number of transactions made by a customer.
- **Units** – Total quantity purchased.
- **Total Purchase** – Total amount spent by each customer.
- **Rank** – Ranking customers according to total purchase.
- **High Value?** – Classifies customers as **Top 10** or **Standard**.
- **Avg Order** – Calculates average purchase value per order.

### Important Excel Functions

- `RANK()` – Ranks customers based on purchase value.
- `IF()` – Classifies customers using conditions.
- `IFERROR()` – Handles formula errors safely.
- `LARGE()` – Returns the highest purchase values.
- `INDEX()` – Returns a value from a selected position.
- `MATCH()` – Finds the position of a value in a range.

---

📊 PIVOT TABLE ANALYSIS

The **pivot table** sheet summarizes transaction data by year.

### Summary Fields

- Year
- Sum of Quantity
- Sum of Unit_Price

### Available Results

- **2024 Quantity:** 527
- **2025 Quantity:** 226
- **Total Quantity:** 753

Pivot Tables help summarize large datasets and make year-wise comparisons easier.

---

🎯 WHAT-IF ANALYSIS

The **What-if analysis** sheet uses scenario analysis to study the effect of unit-price changes.

### Scenarios Included

- **Downside -10%**
- **Downside -5%**
- **Current**
- **Upside +5%**

Analysis Fields

- Scenario
- Unit Price Change
- Projected Revenue
- Projected Profit Proxy
- Revenue Change

This analysis shows how changes in unit price can affect projected revenue and supports business planning.

---

📈 REGRESSION ANALYSIS

The **Regression** sheet contains regression output used to study relationships between variables.

### Main Regression Statistics

- Multiple R
- R Square
- Adjusted R Square
- Standard Error
- Observations

The regression analysis helps understand the strength of a relationship and how well the model explains the data.

---

🔗 LIST COMPARISON, LOOKUP & TEXT FUNCTIONS

The **list compare** sheet contains two customer-name lists and examples of text functions.

### List Comparison

The sheet compares **List A – Customer Names** with **List B – Customer Names** and identifies matching names.

### Text Function Examples

- **Original Name**
- **Initials**
- **First Name**
- **Last Name**
- **Name Length**

Important Excel Functions

- `FILTER()` – Returns matching records from a list.
- `COUNTIF()` – Counts values that meet a condition.
- `UPPER()` – Converts initials into uppercase.
- `LEFT()` – Extracts the first name.
- `RIGHT()` – Extracts the last name.
- `FIND()` – Locates the space between names.
- `LEN()` – Calculates name length.

---

🎛️ KPI DASHBOARD

The **Dashboard** sheet presents key customer transaction metrics in one place.

### Main KPIs

- **Total Revenue**
- **Orders**
- **Units**
- **Average Order Value**
- **Top Product**

The dashboard uses formulas connected to the raw transaction data to calculate and display summary information.

---
📋 DATA STORYTELLING & BUSINESS INSIGHTS

The **Storytelling** sheet explains the main findings from the analysis.

 Key Insights

- **Overall Performance:** Revenue of ₹2,29,192.47 from 250 orders.
- **Customer Activity:** 753 units sold across 250 transactions.
- **Average Order Value:** ₹916.77 per order.
- **Top Product:** Bookshelf – 102 units sold.
- **Category Insight:** Electronics is a major contributor to revenue.
- **Regional Insight:** East region generated the highest revenue.
- **Business Takeaway:** Product and regional analysis can help identify key sales opportunities.

Data storytelling converts calculated results into simple business conclusions.

---

## 🎨 FORMATTING & PRESENTATION

The workbook presents analysis through separate sheets for raw data, formulas, summaries, scenarios, regression, dashboard metrics, and storytelling.

The structure makes it easier to:

- Locate the original dataset
- Review formulas and helper columns
- Study customer rankings
- Compare yearly results
- Test different scenarios
- Understand regression output
- View KPIs and business insights

---

## 🛠️ EXCEL SKILLS DEMONSTRATED

- Data organization
- Date and time functions
- Text functions
- Conditional formulas
- Error handling
- Ranking and statistical functions
- INDEX and MATCH
- FILTER and COUNTIF
- Customer segmentation
- Pivot Table analysis
- What-If Analysis
- Regression Analysis
- KPI creation
- Dashboard preparation
- Data storytelling


🏁 PROJECT SUMMARY

This project demonstrates a complete Excel data-analysis workflow using:

**Data Organization + Formula Analysis + Customer Analysis + Pivot Tables + What-If Analysis + Regression + Lookup Functions + Text Functions + KPI Dashboard + Data Storytelling**

The **raw data** sheet acts as the main source, the **Analysis** and supporting sheets perform calculations, the **Dashboard** presents key metrics, and the **Storytelling** sheet explains the final business insights.
