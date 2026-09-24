# Supermarket Sales Analysis

## Project Description

This project performs a complete Exploratory Data Analysis (EDA) on a supermarket sales dataset containing 500 transactions. The goal is to extract meaningful business insights related to products, branches, cities, categories, customer types, payment methods, sales, quantity, and customer ratings. The project is built using Python and is suitable for a BCA / Data Analytics student.

---

## Problem Statement

Supermarkets generate large amounts of transactional data daily. Without analysis, this data provides no actionable value. This project uses Data Analytics techniques to explore 500 supermarket sales transactions and answer key business questions that can help the supermarket improve performance, inventory, and customer experience.

---

## Objectives

- Load and inspect the supermarket sales dataset.
- Perform data quality checks and clean the data if needed.
- Calculate and verify sales values.
- Analyze sales across products, categories, branches, cities, and customer types.
- Understand payment preferences and customer ratings.
- Visualize key metrics using charts.
- Answer important business questions from the data.
- Provide actionable business recommendations.

---

## Dataset

**Dataset Link:**  
[Supermarket Sales Dataset on Google Sheets](https://docs.google.com/spreadsheets/d/1QIX__4VObHFMEXnRM2xJyXmB5JAB2peHrJcQ41_U9TE/edit?usp=sharing)

**Important Columns:**

| Column        | Description                            |
|---------------|----------------------------------------|
| Invoice ID    | Unique transaction identifier          |
| Date          | Date of the transaction                |
| Branch        | Branch code (A, B, C, D)              |
| City          | City where the branch is located       |
| Customer Type | Member or Normal customer              |
| Gender        | Male or Female                         |
| Product       | Name of the product sold               |
| Category      | Product category                       |
| Quantity      | Number of units purchased              |
| Unit Price    | Price per unit (₹)                    |
| Payment       | Payment method used                    |
| Rating        | Customer rating (3.0 – 5.0)           |
| Sales         | Total transaction value (₹)           |

**Dataset Size:** 500 rows × 13 columns  
**Period:** January 2026 – July 2026  
**Branches:** A (Jaipur), B (Delhi), C (Mumbai), D (Bengaluru)

---

## Technologies Used

- Python 3
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook

---

## Project Structure

```
Supermarket-Sales-Analysis/
│
├── data/
│   └── supermarket_sales.csv
│
├── StudentName_SupermarketSalesAnalysis.ipynb
├── requirements.txt
├── StudentName_ProjectReport.docx
└── README.md
```

---

## Installation

Clone or download this repository, then install dependencies:

```bash
pip install -r requirements.txt
```

---

## How to Run

1. Download the CSV dataset from the Google Sheets link above.
2. Place the file inside the `data/` folder and name it `supermarket_sales.csv`.
3. Open terminal/command prompt in the project folder.
4. Launch Jupyter Notebook:
   ```bash
   jupyter notebook
   ```
5. Open `StudentName_SupermarketSalesAnalysis.ipynb`.
6. Click **Kernel → Restart & Run All** to run the complete notebook.

---

## Analysis Performed

- Data loading and inspection
- Data quality checks (missing values, duplicates, data types, value ranges)
- Data cleaning and preprocessing
- Sales calculation verification (Sales = Quantity × Unit Price)
- Product-level analysis (sales, quantity, transaction count)
- Category-level analysis
- Branch and city performance analysis
- Payment method distribution analysis
- Customer type comparison (Member vs Normal)
- Gender analysis
- Customer rating analysis (overall and by branch/category)
- Monthly and day-of-week sales trend analysis
- Business question answers with calculated values
- Visualizations (bar charts, pie chart, histogram, line chart)
- Key insights and business recommendations

---

## Key Findings

*(Calculated directly from the dataset — 500 transactions)*

| Metric | Value |
|---|---|
| Total Sales | ₹2,44,411.08 |
| Total Transactions | 500 |
| Average Transaction Value | ₹488.82 |
| Average Customer Rating | 3.99 / 5.0 |
| Best-Selling Product | Cheese (₹27,906.30) |
| Lowest-Selling Product | Biscuits (₹3,908.87) |
| Top Category by Sales | Beverages (₹56,108.24) |
| Top Category by Quantity | Beverages (465 units) |
| Best Branch | C – Mumbai (₹72,469.45) |
| Best City | Mumbai (₹72,469.45) |
| Highest Avg Transaction Branch | C – Mumbai (₹506.78) |
| Most-Used Payment Method | UPI (127 transactions, 25.4%) |
| Peak Sales Month | April 2026 (₹52,569.77) |
| Peak Sales Day | Sunday (avg ₹601.97 per transaction) |
| Member Transactions | 296 (59.2% of total) |
| Normal Customer Avg Sale | ₹497.07 (higher than Members at ₹483.14) |
| Highest-Rated Category | Bakery (avg 4.24) |
| Highest-Rated Branch | D – Bengaluru (avg 4.09) |

---

## Business Recommendations

1. **Invest in Beverages and Personal Care** — These are the top-selling categories. Ensure adequate stock at all times.
2. **Promote Cheese, Coffee, and Shampoo** — These three products drive the highest individual sales revenue.
3. **Focus on Mumbai Branch (C)** — It is the top-performing branch in both total sales and average transaction value.
4. **Investigate Jaipur Branch (A)** — It has the lowest total sales and the lowest average customer rating (3.84). Service improvements may be needed.
5. **Promote Bakery and Snacks** — These categories receive the highest customer ratings (4.24 and 4.11) but have relatively low sales — better placement or promotion could increase revenue.
6. **Leverage UPI and Net Banking** — These are the most preferred payment methods. Ensure a smooth digital payment experience.
7. **Review Membership Program Value** — Normal customers have a slightly higher average transaction value (₹497.07) than Members (₹483.14). The membership program may need added incentives.
8. **Plan April Promotions** — April 2026 was the peak sales month. Use this pattern for future planning, offers, and stocking.
9. **Boost Sunday Sales** — Sunday shows the highest average transaction value (₹601.97). Run exclusive Sunday offers to capitalize on this.
10. **Restock High-Quantity Items** — Beverages (465 units), Snacks (443), and Grocery (439) have the highest quantities sold. Monitor stock carefully.

---

## Conclusion

This project analyzed 500 supermarket transactions using Python-based Exploratory Data Analysis. Key findings show that Beverages is the top-selling category, Cheese is the best-selling product, Mumbai branch leads in performance, and UPI is the most popular payment method. April 2026 was the peak sales month. These insights can directly support better inventory management, marketing strategies, and branch operations for the supermarket.

---

## Author

**Name:** *(Enter your name here)*  
**Course:** BCA / B.Sc Data Analytics  
**Institution:** *(Enter your institution name here)*  
**Year:** 2026
