# Power BI Data Modeler Project

## Overview
This project focuses on Data Modeling in Power BI using a Star Schema design. The objective was to build relationships between Fact and Dimension tables, configure cardinality, create hierarchies, and validate the data model using Matrix visuals.

## Dataset Used

### Fact Tables
- Sales_Fact
- Returns_Fact

### Dimension Tables
- Customer_Dim
- Product_Dim
- Region_Dim
- Date_Dim

## Tasks Performed

### Data Preparation
- Imported all Excel files using Power Query
- Applied appropriate data types
- Removed blank rows

### Data Modeling
- Built Star Schema
- Created Primary Key and Foreign Key relationships
- Configured One-to-Many relationships
- Created inactive relationship for ReturnDateKey

### Hierarchies Created
#### Date Hierarchy
Year > Quarter > Month > Date

#### Region Hierarchy
Country > State > City

#### Product Hierarchy
Category > Subcategory > ProductName

### Validation
Verified relationships using Matrix visuals:
- Revenue by Product Category and Region
- Return Reasons by Fiscal Year
- Revenue by Customer Segment

## Tools Used
- Power BI Desktop
- Power Query
- Data Modeling

## Project Files
- Data_Modeler.pbix
- Screenshots
- README.mdss