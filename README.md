# Sales-Performance Analysis-EMT1360-Inc
![](EMT1360Inc.jpg)
## Introduction

Welcome to the Warehouse/Database Design Project focusing on Sales and Performance analysis of EMT1360 Inc . This project aims to provide comprehensive insights and analysis to address key questions and support data-driven decision-making within the company.

**Disclaimer:** _It is important to note that all datasets and reports utilized in this project are fictitious and do not represent any specific company, institution, or country. They have been created solely for the purpose of showcasing the capabilities of POWER BI in data visualization and analysis._
## Problem Statement
EMT1360 is a wholesale novelty goods importer and distributor operating from the Washington Bay area. They are involved in the sales and purchase of goods across 6 major cities(Nevada, Washington, NewMexico, California, Oregon, Arizona)in the USA. The management team find it difficult to make decision across different part of the business. Your company has been consulted to develop a data management system for easy of analytical reporting. They currently do not have a Unified a database system for their Online and online Transactions. Their focus is majorly on reporting on sales and Performance across the 6 States. The business is not quite clear on other specific metrics, but they believe that you will provide needed suggestions that could further help the metrics that they will need as a business.  You have been passed this by your manager and you need to A.  Develop a project document which will include a clear understanding of the business flow EMT1360 and develop a flow diagram showing this. B. Develop a complete road map for developing the warehouse system.

# Project Document: Database Management System for EMT1360
## 1. Introduction:
EMT1360 is a wholesale novelty goods importer and distributor based in the Washington Bay area. The company operates across five major cities in the USA, engaging in sales and purchase transactions. The management team has identified challenges in decision-making across various parts of the business due to the absence of a unified database system for online and offline transactions. This project aims to develop a data management system to facilitate analytical reporting, with a focus on sales and performance analysis across the six states where EMT1360 operates.

# A. Project Document for EMT1360 Inc following Ralf Kimboll model

## 1.Identifying the Business Process of EMT1360:

EMT1360, a wholesale novelty goods importer and distributor based in the Washington Bay area, operates across five major cities in the USA. The business processes involved in EMT1360's operations can be outlined as follows:

**Sales Process**: Customers place orders for goods either online or in-store. Sales transactions are recorded, and products are distributed to customers.
  
**Purchase Process**: EMT1360 purchases goods from suppliers to maintain inventory levels and meet customer demand.
  
**Inventory Management**: EMT1360 manages inventory across its locations to ensure adequate stock availability for fulfilling customer orders.
  
**Customer Management**: Customer information is managed to maintain relationships and provide personalized services.
  
**Performance Analysis**: EMT1360 analyzes sales and performance data to make informed decisions and improve business operations.

## 2. Identify the Grains:

The grains represent the level of detail or granularity at which data is stored and analyzed. For EMT1360's data management system, the grains could include:

- **Transaction Level**: Individual sales transactions, including details such as customer, product, quantity, price, and location.
  
- **Daily/Weekly/Monthly Aggregations**: Aggregated data summarizing sales and performance metrics on a daily, weekly, or monthly basis.

## 3. Choose the Dimensions:

Dimensions are attributes along which data can be analyzed. For EMT1360's data management system, relevant dimensions may include:

**Date/Time**: Time-related attributes such as transaction date, order date, etc.
  
**Customer**: Customer-related attributes such as customer ID, name, location, etc.
  
**Product**: Product-related attributes such as product ID, name, category, etc.
  
**Location**: Location-related attributes such as city, state, etc.
  
**Sales Channel**: Attributes related to sales channels, such as online vs. in-store.
  
**Supplier**: Supplier-related attributes such as supplier ID, name, etc.

## 4. Choose the Measures:

Measures represent the quantitative data that can be analyzed. For EMT1360's data management system, potential measures could include:

- **Sales Revenue**: Total revenue generated from sales transactions.
  
- **Units Sold**: Total quantity of products sold.
  
- **Average Order Value**: Average value of each sales transaction.
  
- **Inventory Levels**: Current inventory levels of products.
  
- **Customer Satisfaction Scores**: Metrics indicating customer satisfaction levels.
  
- **Profit Margins**: Profit margins on sales transactions.

# B. Roadmap for Developing the Warehouse System and Design:**

1. **Requirements Gathering and Analysis:**
   - Meet with stakeholders to understand their requirements and business processes.
   - Define data requirements, including dimensions, measures, and grains.

2. **Data Warehouse Design:**
   - Design the data warehouse schema, including dimension tables, fact tables, and relationships.
   - Define ETL processes for extracting, transforming, and loading data into the warehouse.

3. **Infrastructure Setup:**
   - Set up the necessary infrastructure, including servers, databases, and storage.

4. **Data Integration:**
   - Implement ETL processes to integrate data from various sources into the data warehouse.
   - Ensure data quality and consistency through data cleansing and validation.

5. **Dimensional Modeling:**
   - Develop dimension tables and define hierarchies and attributes.
   - Design fact tables and identify measures and grains.

6. **Data Visualization and Reporting:**
   - Develop dashboards and reports for sales and performance analysis(Power BI or Tableau)
   - Implement interactive visualizations to facilitate data exploration.(Python)

7. **Testing and Validation:**
   - Conduct testing to ensure the accuracy and reliability of data and reports.
   - Validate the warehouse system against stakeholder requirements.

8. **Deployment and Training:**
   - Deploy the warehouse system to production.
   - Provide training to users on accessing and using the system effectively.

9. **Maintenance and Support:**
   - Establish processes for ongoing maintenance, monitoring, and support.
   - Continuously improve the warehouse system based on feedback and changing business needs.

By following this roadmap, EMT1360 can successfully develop and implement a data management system to support sales and performance analysis, enabling data-driven decision-making and improving business outcomes.


