# Global Superstore Sales & Profit Analysis

An end-to-end data analysis project that explores the sales and profit performance of Global Superstore, using **Python (pandas)** for data cleaning and **Tableau Public** for interactive dashboards.

🔗 **Live Dashboard:** [View on Tableau Public](https://public.tableau.com/app/profile/ayush.yadav7680/viz/superstore_17917793831830/Overview)

[![Dashboard 1 & 2](images/dashboard_1.png)](https://public.tableau.com/app/profile/ayush.yadav7680/viz/superstore_17917793831830/Overview)

---

## 📌 Project Overview

Global Superstore sells products across multiple markets, regions and customer segments. The goal of this project is to understand **what drives sales and profit** and to find where the business is losing money, so that better decisions can be made.

## ❓ Business Questions

- Which product categories and sub-categories generate the most sales and profit?
- Which regions and markets perform best, and which perform worst?
- Which customer segments are the most valuable?
- Are there products or regions that make sales but lose profit?
- How do sales and profit change over time?
- How does discounting affect profit?

## 📂 Dataset

- **Raw data:** `data/superstore.csv`
- **Cleaned data:** `data/superstore_cleaned.csv`
- **Size:** 51290 rows and 35 columns
- **Contains:** order details, dates, shipping mode, customer segment, location, product category, sales, quantity, discount and profit

## 🛠️ Tools Used

| Tool | Purpose |
|---|---|
| Python (pandas) | Data cleaning and preparation |
| Jupyter Notebook / VS Code | Writing and running the analysis |
| Tableau Public | Building interactive dashboards |
| GitHub | Version control and project hosting |

## 🔄 Process

### 1. Data Cleaning (Python)
- Loaded the data and checked its shape and data types
- Checked for and handled missing values
- Checked for and removed duplicate records
- Fixed data types (for example, converting date columns)
- Saved the cleaned data as `superstore_cleaned.csv`

### 2. Dashboard Building (Tableau)
- Connected the cleaned data to Tableau Public
- Built worksheets for sales, profit, category, region, segment and time trends
- Combined the worksheets into two interactive dashboards
- Applied a consistent colour palette and layout for readability

## 💡 Key Insights

**Overall performance (2011 to 2014)**
- The business made **$12.64M in total sales** and **$1.47M in total profit**, a **11.6% profit ratio**, across **25,035 orders**.
- Sales and profit grew every year.

**Discounts**
- Discounts above 20% make the business lose money.
- Sub-categories with higher average discounts earn less profit.

**Products**
- Tables is the only sub-category with a loss (-8.5% profit margin).

**Countries**
- Turkey, Nigeria and the Netherlands are the biggest loss-making countries.
- The United States is the most profitable country, followed by China and India.

**Customers**
- The top customer earns about $8.7K, while the worst customer loses about $6.2K.

**Shipping**
- Standard Class takes about 5 days to ship, compared with about 2 days for First Class.
  
## 📁 Repository Structure

```
Global-Superstore-Analysis/
│
├── README.md                          # Project overview, insights and recommendations
├── superstore.csv                     # Raw dataset (51,290 rows, 27 columns)
├── superstore_clean.csv               # Cleaned dataset used in Tableau
├── superstore.ipynb                   # Python (pandas) data cleaning and analysis notebook
├── superstore.twbx                    # Tableau packaged workbook (worksheets + dashboards)
├── Overview.png                       # Dashboard 1: sales, profit, discounts, map, categories
├── Deep Dive.png                      # Dashboard 2: countries, customers, shipping
├── Global Superstore Sales & Profit Analysis Proje...   # Project report
├── Global Superstore is growing but profit leaks ar...  # Presentation 
```

## ▶️ How to Run

1. Clone this repository
```bash
   git clone https://github.com/ayush3112yadav-hub/global-superstore-sales-profit-analysis.git
```
2. Open `notebooks/data_cleaning.ipynb` in VS Code or Jupyter and run all cells
3. Open `tableau/superstore_dashboard.twbx` in Tableau Public, or view the [live dashboard](https://public.tableau.com/app/profile/ayush.yadav7680/viz/superstore_17917793831830/Overview)

## 👤 Author

**Ayush Yadav**

Aspiring Data Analyst | SQL, Python, Tableau, Power BI

🔗 [LinkedIn](https://www.linkedin.com/in/ayush-yadav-914246198)
