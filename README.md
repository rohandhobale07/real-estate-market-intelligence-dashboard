                                     🏠📊 Real Estate Market Intelligence Dashboard 🏠📊

An interactive Power BI dashboard designed to analyze real-estate sales, pricing trends, regional performance, house types, and key market indicators across 100,000 housing records.

📊 Project Overview

The Real Estate Market Intelligence Dashboard transforms a large housing dataset into an interactive business intelligence solution using:

• 🗄️ MySQL
• 📊 Power BI
• 🧮 DAX
• 📗 Microsoft Excel

The project analyzes 100,000 housing records across 607 cities and 4 regions, covering 5 house types and 4 sales types.

The dashboard provides insights into sales performance, pricing trends, regional differences, house-type performance, and year-over-year growth.

🎯 Project Objectives

• Analyze real-estate sales and pricing trends
• Compare sales performance across regions and cities
• Track year-over-year sales growth
• Analyze purchase price and offer price relationships
• Compare different house types and sales types
• Monitor YTD and last 12 months sales
• Analyze average price per square meter
• Identify regional sales and pricing patterns
• Build an interactive business intelligence dashboard

🛠️ Technologies Used

🗄️ MySQL
Database creation, data loading, validation, and SQL analysis

📊 Power BI
Interactive dashboard development and data visualization

🧮 DAX
KPI calculations, measures, and time-based analysis

📗 Microsoft Excel
Dataset inspection and preparation

📁 Dataset

• 📊 100,000 housing records
• 🌍 607 cities
• 🗺️ 4 regions
• 🏠 5 house types
• 💼 4 sales types

🔑 Key Data Fields

• Purchase Price
• Offer Price
• Square Meters (SQM)
• SQM Price
• House Type
• Sales Type
• City
• Area
• Region
• Year Built
• Number of Rooms
• Interest Rate
• Inflation Rate
• Mortgage Credit Bond Yield

🗄️ MySQL Database

The housing dataset was loaded into a MySQL database named HOUSE.

🔄 Database Workflow

1. Created the HOUSE database
2. Imported the Housing Data.csv dataset
3. Created the housing table
4. Loaded the dataset into MySQL
5. Validated the imported data
6. Checked the number of records using SQL

💻 SQL Example

```sql
DROP DATABASE IF EXISTS HOUSE;
CREATE DATABASE HOUSE;
USE HOUSE;

SELECT COUNT(*) FROM `housing data`;
