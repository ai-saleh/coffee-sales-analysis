# Coffee Beans Sales Analysis

## Project Overview
A data analysis project examining coffee bean sales data to uncover business insights using Microsoft Excel.

## Dataset Description
The analysis is based on three primary datasets:
- Orders (1000 records): Contains transaction data with OrderID, dates, quantities
- Customers: Customer information and demographics
- Products: Coffee product details including types, prices, and profits

## Data Quality Notes
- The Orders dataset contains multiple entries per OrderID, indicating separate line items within each order
- [Additional data quality observations will be added as discovered]

## Methodology

### 1. Data Import and Preparation
- Utilizing Power Query (Get Data) in Excel for data import and transformation
- Benefits:
  - Facilitates data cleaning and transformation
  - Enables easy dataset merging
  - Provides reproducible and automated workflows
  - Maintains connection to data sources

### 2. Data Standardization
Implementing standardized naming conventions for clarity and consistency:

#### Orders Table Example:
| Original Name  | Standardized Name | Reasoning |
|---------------|-------------------|-----------|
| Order ID      | OrderID           | Removed spaces for better formula handling |
| Order Date    | DtOrder           | Dt prefix indicates date field |
| Customer ID   | FK_CustomerID     | FK prefix indicates foreign key |
| Product ID    | FK_ProductID      | FK prefix indicates foreign key |
| Quantity      | Quantity          | Maintained as is |

## Project Status
🚧 In Progress

[Additional sections will be added as the project progresses]