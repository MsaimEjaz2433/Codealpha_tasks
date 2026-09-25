# Amazon Gaming Laptops Market Analysis 💻📊

## Project Overview
This project executes a complete data analytics pipeline to evaluate the gaming laptop market on Amazon. Completed as part of the CodeAlpha Data Analytics Internship, this project encompasses data extraction (web scraping), exploratory data analysis (EDA), and interactive data visualization. The objective is to transform unstructured web data into actionable market intelligence, highlighting pricing trends, brand dominance, and hardware configurations.

## Tasks Completed

### Phase 1: Data Extraction & Web Scraping (Task 1)
The foundation of this analysis required building a custom dataset directly from live e-commerce listings. 
* **Tool Used:** Octoparse
* **Process:** Automated a scraping workflow to navigate multiple pages of Amazon search results for "gaming laptops".
* **Extracted Data:** Captured critical product attributes, including laptop titles, prices, RAM sizes, storage capacities, GPU models, and customer ratings.
* **Output:** `Amazon.com _ gaming laptops.csv`

### Phase 2: Exploratory Data Analysis (Task 2)
With the raw data collected, the next step was to clean the dataset and identify market patterns.
* **Tool Used:** Microsoft Excel
* **Process:** Performed data cleansing to handle missing values, standardize text formats, and parse complex strings into numerical columns. Generated summary statistics to understand central tendencies of pricing, discounts, and ratings.
* **Insights:** Mapped out laptop counts by brand and GPU model, and ran correlation analyses examining the relationship between RAM capacity and discounted pricing.
* **Output:** `Amazon.com _ gaming laptops_CLEANED.csv.xlsx`

### Phase 3: Data Visualization (Task 3)
To make the cleaned data accessible and interactive, a comprehensive analytical dashboard was built.
* **Tool Used:** Power BI
* **Process:** Designed an interactive dashboard highlighting key metrics such as average ratings, discount distributions, brand dominance, and hardware trends.
* **Features:** Includes bar charts for brand pricing, scatter plots for hardware cost correlations (RAM/Storage vs. Price), and dynamic slicers to filter data by specifications.
* **Output:** `CodeAlpha_Task3_Amazon_Gaming_Laptop_Dashboard.pbix`

## Repository Structure
* `Amazon.com _ gaming laptops.csv`: The raw dataset extracted from Amazon.
* `Amazon.com _ gaming laptops_CLEANED.csv.xlsx`: The cleaned and formatted dataset after EDA in Excel.
* `CodeAlpha_Task3_Amazon_Gaming_Laptop_Dashboard.pbix`: The interactive Power BI dashboard file.
* `README.md`: Project documentation.

## Tools & Technologies
* **Octoparse:** Web Scraping / Data Extraction
* **Microsoft Excel:** Data Cleaning, EDA, Statistical Summaries
* **Microsoft Power BI:** Data Visualization, Dashboard Creation

## Acknowledgments
This project was developed during the Data Analytics Internship at [CodeAlpha](https://www.codealpha.tech/).