# E-Commerce-Data-Pipeline-End-to-End-Engineering-and-Analytics-with-Salesforce-Snowflake-and-Tableau

## **Project Overview**:

This project demonstrates the full Data Engineering Lifecycle by simulating the data flow from an E-commerce company, from generation to visualization. The goal is to extract, transform, and Load (ETL) data into a cloud-based datawarehouse to perform cleaning and transformation to maintain data integrity and consistency, then finally create a dynamic and interactive dashboard for analytics, insights and story-telling.

The technologies used include Salesforce, Airbyte, Snowflake, and Tableau to replicate real-world data engineering workflows.

## Project Objectives:
- End-to-End Data Engineering Lifecycle: Simulate the ingestion, transformation, and visualization pipeline for an e-commerce dataset
- Proficiency in Tools: Work with Salesforce (data source), Airbyte (ETL tool), Snowflake (data warehouse), and Tableau (data visualization)
- Skills Development: Database creation, schema design, data transformation, and dashboard creation
- Gain experience in data validation, error handling, and dashboard storytelling

## Key Features:
- Data Generation: Generate Account data in Mockaroo and load that data into the Salesforce account
- Data Preparation: Create and configure the database objects in Snowflake
  - One Database
  - Two Schemas (One Stage and One Prod)
  - 3 Dimension Tables and One Fact Tables
  - Data Loading: Utilize Airbyte to extract data from Salesforce and load it into the stage tables in Snowflake
 
- Data Transformation: Implement transformation logic to cleanse, filter, aggregate, and enrich the data in the stage tables
- Data Validation: Validate data transformation and copy the clean data into the Prod tables
- Data Serving and Visualization: Establish a connection to the Snowflake database through Tableau Desktop. Develop a Dashboard of our choosing that analyzes the data we have now ingested
  - One Dashboard
  - Includes at least five different visualizations
  - Properly used containers throughout the dashboard
  - Ability to filter the entire dashboard by a dimension
  - Use a parameter to toggle between two dimensions
- Documentation: A final, formal document that includes; our analysis and insights from the data, the process of building the Tableau Dashboard and all SQL scripts used

## Technology Stack:
- Salesforce: CRM tool for account data generation and management
- Mockaroo: Synthetic data generator
- Airbyte: Automated ETL tool for data extraction and loading
- Snowflake: Cloud-based data warehousing platform
- Tableau Desktop: Visualization tool for creating dashboards

## Key Insights:
-  Witnessed unstable trend in ordered quantities for 2022 and 2023, Peaks were seen in October 2022 and April 2023, could be because of summer and holiday discounts
-  In 2022, the Eco-cycle Recycled Laptop Sleeve was the top-seller, generating over $6,000. In 2023, the Bio-blend Organic Protein Powder led with sales of around $6,626
-  The scatter plot shows most order values cluster below $1,100, with higher quantities and values observed in 2023 compared to 2022
-  Product are priced at 2.7X their manufacturing costs for helathy profit margin
-  Loyal, high-value customers are concentrated in the New England region, particularly in Massachusetts and Virginia

## Tableau Dashboard:
You can view the interactive Tableau Dashboard on [Tableau Public](https://public.tableau.com/app/profile/abbas.ibrahim3274/viz/E-commerceCompanySalesDashboard/Dashboard1).

## Learning Outcomes:
- Gained hands-on experience in implementing a complete data pipeline for an e-commerce business
- Learned to work with industry-relevant tools such as Salesforce, Airbyte, Snowflake, and Tableau
- Developed skills in data integration, transformation, and visualization for real-world applications



