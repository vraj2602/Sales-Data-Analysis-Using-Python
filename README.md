# Sales Data Analyzer

A Python-based data analysis project that processes raw retail sales records, performs data cleaning, extracts actionable insights (such as revenue generation and product popularity), and filters category-specific datasets.

## 📊 Project Overview
This project uses a Jupyter Notebook to ingest and analyze a dataset containing e-commerce/retail transactions. It tracks information such as `OrderID`, `Date`, `Customer`, `Product`, `Category`, `Quantity`, and `Price` to compute revenue statistics and automate report generation.

### Key Features & Queries Covered:
1. **Data Ingestion:** Reading raw CSV transaction data without heavy external dependencies.
2. **Revenue Analysis:** Calculating total overall revenue and filtering revenue by specific custom date ranges.
3. **Category Breakdown:** Isolating and generating filtered datasets (e.g., extracting all data related to the **Electronics** category into a standalone `electricals.csv` file).
4. **Product Analytics:** Sorting and determining top-performing products and customer purchasing behaviors.

## 📁 Repository Structure
* **`sales_data.csv`**: The primary raw dataset containing transactional records (Customer name, Product, Category, Price, Quantity, etc.).
* **`SalesAnalyzer.ipynb`**: The main Jupyter Notebook where data parsing, calculations, and analytical logic are written.
* **`electricals.csv`**: An automatically generated output file containing filtered transactional logs strictly for the Electronics category.

**Author:** Viraj Bhosale

**LinkedIn:** [Viraj Bhosale Profile](https://www.linkedin.com/in/viraj-bhosale-b9125a377?utm_source=share&utm_campaign=share_via&utm_content=profile&utm_medium=android_app)
