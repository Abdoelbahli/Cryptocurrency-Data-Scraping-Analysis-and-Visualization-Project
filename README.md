# Cryptocurrency Data Scraping, Analysis, and Visualization Project

## Overview

This project involves scraping cryptocurrency data from Yahoo Finance, performing data analysis, and visualizing the results using **Matplotlib** and **Power BI**. The goal is to gather comprehensive data on various cryptocurrencies, analyze trends, and create interactive dashboards and visualizations for better insights.

---

## Project Components

### 1. **Data Scraping**
- **Tools Used**: Python, BeautifulSoup, Requests, Pandas
- **Description**: The project starts with scraping cryptocurrency data from Yahoo Finance. The data includes various metrics such as symbol, name, price, change, market cap, volume, and circulating supply.
- **Key Features**:
  - Checks Yahoo Finance's `robots.txt` to ensure scraping is allowed.
  - Scrapes data from multiple pages to gather a comprehensive dataset.
  - Stores the scraped data in a Pandas DataFrame for further analysis.

---

### 2. **Data Cleaning and Transformation**
- **Tools Used**: Python, Pandas
- **Description**: The scraped data is cleaned and transformed to ensure it is in a usable format for analysis. This includes converting volume and market cap data into numeric values.
- **Key Features**:
  - Converts volume and market cap data from strings to numeric values.
  - Handles missing or inconsistent data.

---

### 3. **Data Analysis**
- **Tools Used**: Python, Pandas
- **Description**: The cleaned data is analyzed to extract meaningful insights. This includes calculating price change statistics, market cap weighting, and other relevant metrics.
- **Key Features**:
  - Calculates price change statistics.
  - Computes market cap weighting for each cryptocurrency.

---

### 4. **Data Visualization with Matplotlib**
- **Tools Used**: Matplotlib
- **Description**: The analyzed data is visualized using **Matplotlib** to create static charts and graphs. These visualizations provide insights into cryptocurrency trends, market performance, and other key metrics.
- **Key Features**:
  - Line charts for price trends over time.
  - Bar charts for market cap distribution.
  - Scatter plots for volume vs. price changes.
  - Histograms for price change distributions.

---

### 5. **Power BI Dashboard**
- **Tools Used**: Power BI
- **Description**: The analyzed data is also visualized using **Power BI** to create interactive dashboards. These dashboards provide dynamic insights into cryptocurrency trends, market performance, and other key metrics.
- **Key Features**:
  - Interactive visualizations for price trends, market cap distribution, and volume analysis.
  - Filters and slicers for dynamic data exploration.

---

