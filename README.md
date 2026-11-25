# 📊 E-Commerce Sales Analysis | Power BI

### Data Transformation • Power Query • Data Modeling • Data Preparation

## 📌 Project Overview

This project focuses on transforming and modeling e-commerce sales data using **Microsoft Power BI**. It involves importing multiple datasets, performing data transformation using Power Query Editor, handling missing and duplicate records, merging tables, and establishing relationships to create a structured data model for analysis.

## 🎯 Project Objectives

- Import and transform multiple datasets using Power Query.
- Clean and standardize data to improve data quality.
- Create custom and conditional columns for additional analysis.
- Merge datasets using appropriate join operations.
- Establish relationships between tables to build a structured data model.
- Apply sorting, filtering, grouping, and aggregation techniques.

## 📂 Dataset Information

The project uses three datasets:

| Dataset | Description |
|---|---|
| List of Orders | Order details, customer information, dates, and locations |
| Order Details | Sales, profit, quantity, category, and sub-category information |
| Sales Target | Monthly sales targets by category |

## 🛠️ Tools & Technologies

- **Microsoft Power BI**
- Power Query Editor
- Data Transformation
- Data Modeling
- Data Relationships

## 🔄 Project Workflow

**1. Data Import & Transformation**
- Imported three CSV datasets into Power BI.
- Restricted the List of Orders table to the first 500 rows.
- Changed column data types appropriately.
- Converted CustomerName into Proper Case.
- Merged State and City columns to create a Location column in the format City, State.

**2. Custom & Conditional Columns**
- Created a Profit Margin column using Profit / Amount.
- Created a conditional Profit Status column with three classifications:
  - Loss
  - Break-Even
  - Profit

**3. Data Merging & Cleaning**
- Merged List of Orders and Order Details using Order ID.
- Identified missing values and considered appropriate handling strategies.
- Checked for duplicate records and defined suitable handling strategies.

**4. Sorting, Filtering & Aggregation**
- Sorted orders by Order Date in descending order.
- Applied state-based filtering for regional analysis.
- Grouped data to calculate:
  - Count of Order ID
  - Average Profit by Category
  - Total Amount by Sub-Category
  - Total Sales Target by Month

**5. Data Modeling & Relationships**

Established relationships between datasets:

- List of Orders ↔ Order Details using Order ID.
- Order Details ↔ Sales Target using Category.

Created a structured data model using Power BI's Manage Relationships functionality.

## 📈 Key Skills Demonstrated

- Data Import & Data Preparation
- Power Query Transformations
- Data Cleaning & Standardization
- Custom Column Creation
- Conditional Column Logic
- Table Merging & Grouping
- Data Aggregation
- Data Modeling & Relationships
- Sorting & Filtering

## 💡 Project Outcome

Developed practical experience in transforming raw e-commerce datasets into structured, analysis-ready data using Power BI. Strengthened my understanding of Power Query operations, data preparation techniques, table relationships, and data modeling fundamentals.

---



⭐ Feel free to explore my repository and connect with me!
