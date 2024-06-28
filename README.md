# Apache-Spark-ETL-with-Task-Sceduler

# Alien Bank Data Transformation Project

## Executive Summary
Alien Bank is undergoing a data-centric transformation to enhance operational efficiency, improve customer service, and enable effective decision-making through advanced analytics. This project focuses on building a robust data pipeline for extracting, transforming, and loading (ETL) data, aimed at improving data governance and analytics readiness.

## Business Problem Statement
Alien Bank faces challenges with managing vast customer transaction data stored in disparate systems, hindering comprehensive analysis and timely decision-making. Issues such as data integrity, redundancy, and accessibility need to be addressed to streamline data management and ensure reliable data utilization.

## Objectives
- **Streamline Data Processes:** Automate ETL processes to reduce manual intervention and errors.
- **Ensure Data Quality:** Implement checks and transformations to maintain high data quality standards.
- **Data Normalization:** Structure data into 2nd or 3rd Normal Form to reduce redundancy and improve consistency.
- **Improve Data Accessibility:** Centralize data in a PostgreSQL database for easier access and complex analytics.
- **Enhance Decision Making:** Provide clean, reliable data for informed business decisions.

## Benefits
- **Improved Data Quality:** Ensures accuracy and reliability, minimizing errors.
- **Enhanced Analytical Capabilities:** Enables efficient data insights and informed decisions.
- **Operational Efficiency:** Automates workflows to speed up processes and reduce time to insights.
- **Cost Reduction:** Optimizes data storage and processing costs.
- **Scalability:** Scales to meet growing data demands and complexity.

## Tech Stack
- **Python:** Scripting, data manipulation, and process automation.
- **SQL:** Data querying and manipulation.
- **PySpark:** Handling large datasets and distributed data processing.
- **PostgreSQL:** Relational database system for data storage and management.
- **Windows Task Scheduler:** Automating and scheduling ETL jobs.
- **GitHub:** Version control and collaboration.

## Data Source
- [Link to Data Source](Data Source)

## Data Architecture
### Data Extraction
- **Setup Spark Session:** Initialize PySpark session for distributed data processing.
- **Extract Historical CSV Files:** Read historical transaction data using PySpark for scalable preprocessing.

### Data Transformation
- **Clean Dataset:** Handle missing values, standardize formats, and remove duplicates.
- **Normalize Data:** Organize data into 2NF or 3NF to reduce redundancy and improve integrity.

### Data Loading
- **Load Data into PostgreSQL:** Use SQL and PySpark to load normalized data into PostgreSQL for efficient storage and analysis.

## Conclusion
This project addresses immediate data management challenges at Alien Bank while laying a foundation for continuous improvement and scalability in data strategy. By enhancing data quality, accessibility, and analytics capabilities, Alien Bank aims to achieve greater operational efficiency and informed decision-making.

 
