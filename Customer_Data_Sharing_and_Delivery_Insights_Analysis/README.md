# Customer Data Sharing and Delivery Insights Analysis

## Introduction
This project, Customer Behavior Analysis, is part of a Proof of Concept (POC) to evaluate the viability of adding a delivery option at Acme Gourmet Meals (AGM) to increase sales, expand the customer base, and improve profitability. The data engineering team is working in collaboration with the data science team to process and validate delivery data from a third-party provider, Peak Deliveries. The project focuses on processing customer data, mapping product information, and conducting preliminary analyses to provide executives with valuable insights about customer behavior and data quality.

## Project Description
AGM is trialing a three-month delivery option exclusively at the Berkeley store in partnership with Peak Deliveries, a service that takes a percentage cut of the product pricing in lieu of a delivery fee. Since AGM is not sharing customer information with Peak, customers must create new accounts through Peak. This POC includes several data engineering tasks, such as creating product mapping tables, parsing daily sales JSON files, loading and validating data into staging tables, and performing data cleansing and preliminary analytics on customer behavior.

The ultimate goal is to determine the quality of customer data provided by Peak, assess whether AGM can continue withholding direct customer data from third-party services, and provide management with actionable insights based on early analytics.

## Key Questions
1. How accurate and consistent is the customer data provided by Peak?
2. What is the preliminary customer behavior based on initial delivery data?
3. Is it feasible for AGM to continue withholding direct customer data from Peak?
4. Are there potential areas for data quality improvement in the customer information?
5. How effective is Peak’s delivery service within the defined 5-mile radius of the Berkeley store?
6. What insights can we gain about customer tipping behavior (if available indirectly)?

## Technologies Used
- SQL: For creating, loading, and validating tables in the staging environment.
- Python: Used for parsing and transforming JSON files, data cleansing, and initial analysis.
- Data Wrangling: Techniques to clean and prepare customer data.
- AWS: For data storage, processing, and staging in a cloud environment.
- Docker: Containerized environments to ensure consistency across development and production stages.
- JSON: Used for daily data transfer between Peak Deliveries and AGM.
- Jupyter Notebooks: For data exploration and documentation of initial analyses.
