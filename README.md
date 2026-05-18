# Part 1: Data Analysis and Insight - Used Car Inventory

## 1. Data Overview
* **Source & Context**: A dataset of used car listings, analyzed to understand technical attributes influencing market supply and usage patterns.
* **Structure**: The dataset contains roughly 150 rows and 7 variables (Model, Year, Mileage, Color, Type, Fuel, Price).

## 2. Data Cleaning
* **Missing Values**: Imputed empty cells in 'Color', 'Type', and 'Fuel' columns with the placeholder "Unknown".
* **Duplicates**: Identified and removed exact duplicate rows to ensure data integrity.
* **Standardization**: Renamed the inaccurate "Km/h" column to "Mileage" and deliberately removed the "Price" column to pivot the analytical focus toward inventory volume and wear metrics.

## 3. Descriptive Statistics & Insights
* **Insight 1: Transmission Market Dominance**
  * Automatic transmission vehicles account for the vast majority of the market inventory compared to manual units. This clearly reflects modern consumer trends prioritizing driving convenience in urban environments.
* **Insight 2: Mileage Distribution Across Categories**
  * Manual transmission vehicles exhibit a significantly higher average accumulated mileage. This indicates that manual vehicles in this portfolio are predominantly older models or utilized heavily for commercial and service purposes.

*(Note: Please refer to the attached Excel file in this repository to view the full Cleaned Data and visual Dashboard).*# MIS-311
