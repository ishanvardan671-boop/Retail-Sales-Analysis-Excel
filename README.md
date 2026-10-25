# 🛍️ Retail Sales Analysis using Excel

An Excel-based data analytics project to analyse retail sales, understand customer purchasing behaviour, and find useful business insights from 2022 sales data.

---

## 📌 About the Project

Vrinda Store wanted to understand its 2022 sales performance and customer behaviour to improve sales in 2023.

In this project, I used Microsoft Excel to clean and process raw data, perform sales analysis, create charts, and build an interactive dashboard.

The main goal was to convert raw sales data into meaningful insights that could help the business make better decisions.

**Learning Reference:** This project was inspired by an Excel sales analysis tutorial by Rishabh Mishra. I used the tutorial as a learning reference and practised the analysis workflow, documented my steps, and recorded my observations.

## 🎯 Project Objectives

- Clean and prepare raw sales data.
- Analyse monthly sales and order trends.
- Understand customer purchasing behaviour.
- Identify the top-performing states and sales channels.
- Compare customer age groups and gender.
- Create charts and an interactive Excel dashboard.
- Suggest business strategies based on the findings.

## 🧰 Tools & Skills Used

- Microsoft Excel
- Data Cleaning
- Data Processing
- Excel Formulas (`IF`, `TEXT`)
- PivotTables and PivotCharts
- Sorting and Filtering
- Top 5 Analysis
- Data Visualization
- Slicers and Report Connections
- Interactive Dashboard
- Business Insights

## 📂 Dataset Overview

The dataset contains order-level information about customers, products, sales, and shipping.

Important columns include:

| Column       | Description                          |
| ------------ | ------------------------------------ |
| Order ID     | Unique order identification          |
| Customer ID  | Customer identification              |
| Gender       | Customer gender                      |
| Age          | Customer age                         |
| Date         | Order date                           |
| State        | Customer's state                     |
| Channel      | Sales platform                       |
| Category     | Product category                     |
| Size         | Product size                         |
| Qty          | Quantity ordered                     |
| Amount       | Order amount                         |
| Ship City    | Shipping city                        |
| Ship State   | Shipping state                       |
| Ship Country | Shipping country                     |
| B2B          | Business-to-business order indicator |

Other fields include Index, SKU, Currency, and shipping-related information.

## ❓ Business Questions

The project answers the following questions:

1. How do monthly sales and orders compare?
2. Which month recorded the highest sales and orders?
3. Who purchased more — men or women?
4. What were the different order statuses in 2022?
5. Which states contributed the most to sales?
6. How does order contribution vary by age group and gender?
7. Which sales channels contributed the most?
8. Which product categories performed best?

## 🔄 Project Workflow

### 1. Data Cleaning 🧹

The first step was to check and prepare the raw data before starting the analysis.

- Checked for duplicate and missing values.
- Reviewed inconsistent values in the Gender column.
- Standardised gender entries where required.
- Prepared the dataset for further analysis.

### 2. Data Processing ⚙️

I created additional columns to make the analysis easier.

**Age Group**

Used an `IF` formula to classify customers into age groups.

Example formula:

```excel
=IF(E2>=50,"Senior",IF(E2>=30,"Adult","Teenager"))
```

**Month**

Used the `TEXT` function to extract the month from the order date.

Example formula:

```excel
=TEXT(G2,"mmm")
```

*Note: Cell references may differ depending on the column positions in the worksheet.*

### 3. Data Analysis & Visualization 📊

I used PivotTables and PivotCharts to answer the business questions.

**Monthly Sales vs Orders Chart**

- Compared monthly sales and order counts in a single chart.
- Used a chart format that makes monthly trends easier to understand.

**Order Status Chart**

- Analysed the distribution of different order statuses.
- Used order status and order ID in the PivotTable.

**Top 5 States Chart**

- Compared state-wise sales.
- Sorted the results and applied a Top 5 filter to identify leading states.

**Age Group vs Gender Chart**

- Compared order contribution across age groups and genders.
- Used the percentage of grand total to understand customer segments.

**Sales Channel Chart**

- Compared order contribution across different sales channels.
- Analysed the percentage contribution of each channel.

**Product Category Analysis**

- Examined category-wise sales to understand which product categories performed better.

### 4. Dashboard Creation 🎨

After creating the charts, I organised the analysis into an Excel dashboard.

The dashboard uses:

- PivotCharts for visual representation.
- Consistent chart titles and formatting.
- Data labels where useful.
- Clean backgrounds and reduced chart clutter.
- Slicers for interactive filtering.
- Report Connections to connect slicers with relevant PivotTables.

The available slicers allow users to filter the dashboard by fields such as Month, Channel, and Category.

## 💡 Key Insights

Based on the findings recorded in my handwritten analysis notes:

- **Gender:** Women contributed approximately 65% of purchases.
- **Top States:** Maharashtra, Karnataka, and Uttar Pradesh were identified as leading states.
- **Age Group:** Customers aged 30–49 years were recorded as a major contributing segment, at approximately 50%.
- **Sales Channels:** Amazon, Flipkart, and Myntra together contributed approximately 80%, according to my analysis notes.

*These figures are recorded from my project notes and should be verified against the final Excel workbook before being used for business decisions.*

## 📈 Business Recommendations

Based on these observations, the store could:

- Run targeted offers for customer segments that contribute strongly to sales.
- Focus marketing campaigns on high-performing states.
- Review channel-wise sales before planning promotions.
- Use monthly sales trends to support inventory and seasonal planning.
- Analyse product categories to identify opportunities for improvement.

These recommendations are suggestions based on the analysis, not guaranteed business outcomes.

## 📚 What I Learned

Through this project, I practised:

- Cleaning and preparing raw data in Excel.
- Using formulas to create useful analytical columns.
- Creating PivotTables and PivotCharts.
- Analysing customer behaviour and sales trends.
- Applying Top 5 filters and percentage calculations.
- Building an interactive dashboard using slicers.
- Presenting data findings in a simple business-friendly format.

##

## 🙏 Acknowledgement

I would like to thank **Rishabh Mishra** for the Excel tutorial that helped me learn the workflow used in this project. The tutorial served as a learning reference while I practised data cleaning, analysis, chart creation, and dashboard building.

---

## 👨‍💻 Author

**Ishan Vardan**

Aspiring Data Analyst | Excel | Data Analytics

[GitHub Profile](https://github.com/ishanvardan671-boop)

---

⭐ If you find this project useful, feel free to explore the repository and share your feedback.
