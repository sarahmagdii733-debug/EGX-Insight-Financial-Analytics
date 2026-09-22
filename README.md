# EGX Insight – Financial Analytics Platform

## 📊 Project Overview

EGX Insight is an end-to-end financial data analytics project designed
to extract, transform, store, analyze, and visualize financial
statement data for companies listed on the Egyptian Exchange (EGX).

The project combines Python web scraping, a Streamlit application,
SSIS ETL pipelines, SQL Server, data warehousing, and Power BI
financial dashboards.

---

## 🎯 Project Objective

The main objective of EGX Insight is to build an automated financial
analytics workflow that transforms raw financial statement data into
structured and interactive financial insights.

The platform extracts financial data from Stock Analysis, standardizes
the data, loads it into SQL Server, and presents financial KPIs through
interactive Power BI dashboards.

---

## 🔄 Data Pipeline

```text
Stock Analysis
      ↓
Python Web Scraping
      ↓
Data Cleaning & Standardization
      ↓
CSV / Structured Financial Data
      ↓
SSIS ETL
      ↓
SQL Server
      ↓
Bronze → Silver → Gold
      ↓
Star Schema
      ↓
Power BI
      ↓
Financial Insights
🛠️ Technologies Used
Python
Pandas
Requests
Playwright
Streamlit
SQL Server
SSIS
Power BI
DAX
Power Query
Data Warehousing
Star Schema
🐍 Python Data Extraction

Python is used to extract financial statements including:

Income Statement
Balance Sheet
Cash Flow Statement

The extraction supports different reporting periods including:

Yearly
Quarterly
Trailing Twelve Months (TTM)

The data is cleaned and standardized into a structured format containing:

Company
Statement
Line Item
Period
Amount
🌐 Streamlit Application

A Streamlit application was developed to provide a user-friendly
interface for financial data extraction.

The user can select a company and reporting period and generate
structured financial data that can be downloaded a
🗄️ SQL Server & Data Warehouse

SQL Server is used to store and organize the financial data.

The project follows a layered data architecture:

Bronze Layer

Raw financial data.

Silver Layer

Cleaned and standardized financial data.

Gold Layer

Business-ready analytical data.

The final analytical structure follows a Star Schema including:

Fact_Financials
DimAccount
DimCompany
DimStatement
DimCalendar
🔄 SSIS ETL

SQL Server Integration Services (SSIS) is used as part of the ETL
workflow to transform and load financial data into SQL Server.

The ETL workflow includes:

Flat File Source
Data Conversion
Derived Column
Data Transformation
SQL Server Destination
📈 Power BI Dashboards

The project contains five financial analytics dashboards:

1. Financial Performance

Provides an overview of financial performance and major financial KPIs.

2. P&L and Cost Structure

Analyzes revenue, expenses, profitability, and cost structure.

3. Financial Position & Capital Structure

Analyzes assets, liabilities, equity, and capital structure.

4. Liquidity, Solvency & Leverage

Analyzes liquidity and financial leverage indicators.

5. Working Capital & Asset Utilization

Analyzes working capital efficiency and asset utilization.
📊 Financial KPIs

The dashboards include financial metrics such as:

Revenue
Gross Profit
EBITDA
Net Income
Gross Margin
EBITDA Margin
Net Income Margin
ROE
Current Ratio
Quick Ratio
Debt to Equity
Interest Coverage
DSO
DIO
DPO
Cash Conversion Cycle
