# Car Sales Dashboard using Power BI

## Objective

The goal of this project was to analyze car sales data to track total revenue, units sold, dealer performance, customer preferences by region, and vehicle styles.

*Dataset Source*: [Car Sales Dataset (Excel)](https://github.com/Mukul6790/Car-Sales--Data-Analysis-and-Dashboard/blob/main/Car%20Sales.xlsx)

---

## Process

### 1. Data Collection and Cleaning
- Imported the dataset from an Excel file.
- Fields included: car ID, sales date, dealer name, customer name, car model, total sale amount, color, engine type, and transmission.
- Used Power Query to:
  - Remove duplicates
  - Handle null values
  - Convert and standardize data types

### 2. Data Modelling
- Created a calendar table for time-based analysis.
- Established relationships between the main dataset and the calendar table for accurate trend reporting.

### 3. DAX Measures
- Defined custom measures to calculate:
  - Year-to-date sales
  - Monthly total sales
  - Average selling price
  - Total cars sold
  - Percentage changes
- Applied conditional formatting to highlight trends.

### 4. Dashboard Design
- Built two dashboards:
  - *Overview Dashboard*: Summarized high-level trends
  - *Details Dashboard*: Focused on transaction-level analysis
- Added filters for:
  - Body style
  - Transmission type
  - Engine type
  - Dealer name

### 5. Visual Elements
- Used the following visuals in Power BI:
  - Line charts for trends
  - Pie charts for body style and color preferences
  - Maps for regional sales
  - Bar charts for brand-wise performance
  - Slicers and KPI cards for interactivity

---

## Dashboard Snapshots

- *Overview Dashboard*:  ![Details](https://github.com/mukul0030/Car-Sales--Data-Analysis-and-Dashboard/blob/main/Car%20Sales%20Project%20Screenshot%201.png)


- *Details Dashboard*:  
  ![Details](https://github.com/mukul0030/Car-Sales--Data-Analysis-and-Dashboard/blob/main/Car%20Sales%20Project%20Screenshot%202.png)

---

## Key Insights

- Year-to-date sales exceeded *$370 million* with over *13,000 cars sold*.
- *SUV* and *Sedan* were the most preferred body styles.
- *Pale white* and *black* were the most popular colors.
- *Ford* and *Chevrolet* were the top-performing brands.
- Regions like *Scottsdale* and *Aurora* had the highest sales.
- Dealer *Buddy Storbeck’s Diesel Service* recorded one of the highest individual sale values.
- Customer preferences by color, region, and body style were effectively visualized through segmentation.

---

## Conclusion

This project demonstrates my ability to:
- Clean and model complex datasets
- Create calculated measures using DAX
- Design interactive dashboards in Power BI

It highlights how data visualization can help extract meaningful business insights, supporting better decision-making based on customer behavior and sales trends.
