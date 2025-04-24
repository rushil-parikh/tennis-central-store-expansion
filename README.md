# 🎾 Tennis Central: Data-Driven Store Expansion

![4910af77-9990-434c-bc84-3e678ca010a1](https://github.com/user-attachments/assets/62ed19e5-f4b0-4826-a3a7-0e0164e99cca)


---

## 📖 Table of Contents
- [Quick Intro](#-quick-intro)
- [About Tennis Central](#-about-tennis-central)
- [Objective of the Project](#-objective-of-the-project)
- [Business Problems](#-business-problems)
- [Analytical Questions](#-analytical-questions)
- [Dataset & Challenges](#-dataset--challenges)
- [Data Preparation Steps](#-data-preparation-steps)
- [Python Data Cleaning](#-python-data-cleaning)
- [Power BI Data Preparation](#-power-bi-data-preparation)
- [Semantic Model](#-semantic-model)
- [Dashboard & Visualization](#-dashboard--visualization)
- [Answers to Analytical Questions](#-answers-to-analytical-questions)
- [Recommendations](#-recommendations)
- [Conclusion](#-conclusion)

---

## 🚀 Quick Intro
Hi! I'm Rushil Parikh, and this repository highlights my work analyzing sales data for Tennis Central. I built insights and visualizations to help the company set up a new store, optimize inventory, improve staffing, and boost overall profitability.

## 🏢 About Tennis Central
Tennis Central is a specialized sports equipment and apparel store situated inside tennis clubs. They sell tennis rackets, strings, balls, shoes, clothing, accessories, and provide professional racket stringing and maintenance services. The store primarily caters to tennis enthusiasts and club members who regularly require high-quality tennis gear and related services.

## 🎯 Objective of the Project
Tennis Central plans to open a new store at a different club location. The goal is to ensure the new store operates smoothly and profitably from day one by accurately forecasting demand, managing inventory efficiently, scheduling staff effectively, and creating targeted marketing strategies based on customer behavior.

## ⚠️ Business Problems
- Risk of overstocking or understocking due to unclear product demand.
- Operational inefficiencies from improper staffing during busy sales periods.
- Higher product returns impacting overall customer satisfaction.

## ❓ Analytical Questions
I addressed the following questions to clearly understand the business challenges:
- Which product categories generate the most revenue?
- What are the top-selling products in each category?
- What products have the lowest sales?
- Which days of the week see higher sales?
- What hours during the day have peak sales?
- Which products are frequently purchased together?
- Which products are returned most often?

## 📊 Dataset & Challenges
The dataset used includes historical sales records from Tennis Central’s in-store sales via Lightspeed (POS) and online sales from Shopify. Data was provided in CSV format. Challenges encountered included inconsistent formats, missing data, and the need for substantial data cleaning.

## 🧹 Data Preparation Steps
I addressed these data issues by:
- Removing unnecessary columns ('Sale Completed Date', 'Customer Type').
- Standardizing column names for clarity.
- Splitting date and time into separate columns.
- Correcting data types (numeric and datetime formats).
- Checking for and handling null values and outliers.

## 🐍 Python Data Cleaning
In Python (Pandas), I performed:
- Removal of irrelevant columns.
- Renaming columns ('Customer_ID', 'Item_Description', 'Quantity_Sold', 'Total_Sales').
- Splitting 'Sale Completed Time' into separate 'Date_Of_Sale' and 'Time_Of_Sale'.
- Converting data types for accurate analysis.
- Removing null values and incorrect or invalid customer IDs.

## 🛠️ Power BI Data Preparation
Using Power Query in Power BI, I:
- Loaded and cleaned CSV data.
- Created new informative columns such as 'Brand', 'Category', 'Day_of_Week', 'IsWeekend', 'Repeat_Customer', and 'Returned_Item'.
- Built dimension tables (Date, Product, Customer) and one fact table (Sales).
- Structured the data using a clear star schema for better analytical efficiency.

![Screenshot 2025-04-24 163153](https://github.com/user-attachments/assets/de435922-7e6b-4d7c-82d6-574989617644)

## 🌐 Semantic Model
I established clear relationships between:
- Fact Table: Detailed sales data.
- Dimension Tables: Date, Customer, Product.
- Proper relationships enabled accurate, interactive visualizations on the dashboard.

## 📈 Dashboard & Visualization
The dashboard built in Power BI consists of:

1. **Homepage Overview:**
   - Overall sales performance, average transaction size, monthly sales trends, and brand popularity.

2. **Product Categories:**
   - Top-performing categories such as Strings & Services and Rackets, and lower-performing categories like Bottles.

3. **Top & Lowest Sales:**
   - Highest revenue-generating products (e.g., Tennis Labour services, Wilson Balls).
   - Least performing products identified for potential discontinuation.

4. **Sales by Week:**
   - Mondays and Fridays are top sales days; Sundays and Wednesdays need strategic attention.

5. **Sales by Time:**
   - Peak sales occur in the morning; minimal activity in evening/night hours.

6. **Products Bought Together:**
   - Common product combinations, such as racket purchases coupled with stringing services.

7. **Top Returns:**
   - Identification of products frequently returned, highlighting areas needing improvement.

![Screenshot 2025-04-16 225443](https://github.com/user-attachments/assets/000f4536-a027-467c-b728-5f39dd5afcb2)

## ✅ Answers to Analytical Questions
- Clearly identified top revenue categories (Strings & Services, Rackets).
- Highlighted best and worst-performing products to prioritize stocking.
- Defined peak sales times (mornings) and high-sales days (Mondays and Fridays).
- Uncovered frequent product return trends to inform quality improvements.

## 💡 Recommendations
- Prioritize inventory and promotional strategies around top-performing products and categories.
- Optimize staffing levels based on peak sales insights.
- Offer bundled products and services, leveraging purchase patterns.
- Consider discontinuation or reduced stocking of persistently underperforming products.

## 🎉 Conclusion
Through comprehensive data analysis and visualization, this project equips Tennis Central with strategic insights into product performance, customer purchasing behaviors, and operational efficiencies. By implementing these insights, Tennis Central can ensure a successful and profitable launch of their new store.
