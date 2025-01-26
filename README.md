**BuySmart: Cloud-Based Data Warehousing for E-Commerce**

*Project Overview*

BuySmart is a cloud-based data warehousing project designed to support advanced analytics for an online electronics store. The project integrates transactional data (OLTP) into a structured analytical database (OLAP) to facilitate insights into sales, customer behavior, and product performance. Using a star schema design, the system provides a scalable and efficient architecture for querying multidimensional data.

*Key Features*

--> End-to-End ETL Pipeline: Built an automated data pipeline using AWS Glue to extract, transform, and load data from Amazon S3 into Amazon Redshift.

--> Star Schema Design: Modeled data with seven dimension tables (e.g., Time, Country, Product) and a Sales Fact table to enable fast and flexible OLAP operations.

--> OLAP Operations: Implemented roll-ups, drill-downs, slicing, dicing, and pivoting to uncover trends, identify key performance indicators, and analyze customer feedback.

--> Data Transformation: Processed raw data from CSV and JSON files into a query-ready format, including hierarchical dimensions like Country → State → City.

--> Workflow Automation: Utilized AWS Glue Crawlers and Lambda functions to preprocess data and automate schema detection.

*Architecture*

The architecture follows a three-layered approach:

1) Data Ingestion Layer: Raw data ingestion from CSV and JSON files into S3.

2) Data Processing Layer: Data transformation using AWS Glue and PySpark, leveraging the Glue Data Catalog for metadata management.

3) Data Storage Layer: Analytics-ready datasets stored in Amazon Redshift for reporting and business intelligence.

*Technologies Used*

--> Cloud Services: AWS Glue, Amazon Redshift, S3, Lambda, Athena, QuickSight

--> Programming Languages: Python, SQL

--> Data Modeling: Star schema with surrogate keys and hierarchies for time and geography dimensions

*Insights & Future Scope*

--> Current Insights: Enabled sales trend analysis, product popularity metrics, and customer behavior insights.

--> Future Enhancements: Extend the schema to support predictive analytics, add machine learning integration, and optimize query performance for larger datasets.
