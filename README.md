# Financial Data SQL-Based Application

## Team Members

| Name              | Roll Number |
|-------------------|-------------|
| Aadvik Mehrotra   | 2311101     |
| Gourav Pandey     | 2311139     |
| Nitai Satapathy   | 2311163     |
| Saksham Gupta     | 2311184     |
| Suryansh Sharma   | 2311191     |

---

## Project Overview

This project is a part of our Database Management System (DBMS) assignment where we developed a SQL-based application using **Jupyter Notebook**, **Python (Pandas & SQLite3)**, and **web scraping** tools. The primary goal was to collect real-time financial data from the web, store it in a SQLite database, and perform various SQL queries.

---

## Features Implemented

1. **Web Scraping**: Scraped financial data (e.g., stock or company data) from a live website using `pandas.read_html`.
2. **Database Creation**: Created a SQLite database (`finance.db`) and inserted the scraped data into a table.
3. **SQL Query Demonstration**: Applied a wide range of SQL statements in the Jupyter Notebook.

## SQL Concepts Used
1. **Web Scraping**: Scrapes financial data (stock symbols, prices, volumes, market cap) from [Yahoo Finance Most Active Stocks](https://finance.yahoo.com/most-active).
2. **Database Creation**: Creates an SQLite database (`finance.db`) and a table (`stocks`) to store the scraped data.
3. **SQL Queries**: Executes queries demonstrating the following SQL statements:
   - **WHERE**: Filters stocks with prices greater than 100.
   - **GROUP BY**: Groups stocks by market capitalization and counts occurrences.
   - **ORDER BY**: Sorts stocks by price in descending order.
   - **LIMIT**: Retrieves the top 5 stocks from the dataset.
   - **AS**: Renames columns (e.g., `Symbol` to `Ticker`, `Price` to `Stock_Price`).
   - **HAVING**: Filters groups with an average price greater than 100.
   - **BETWEEN AND**: Selects stocks with prices between 200 and 350.
   - **AVG, SUM, COUNT**: Calculates the average price, total price, and count of stocks.
   - **DISTINCT, UPDATE, INSERT**: Lists unique market caps, updates a stock price (example with 'AAPL'), and inserts a test record.
   - **LIKE**: Filters stocks with company names containing "Inc".

---
## License
This project is licensed under the MIT License.

## Acknowledgments
[Yahoo Finance](https://finance.yahoo.com) for providing the financial data.