Data Warehouse and Analytics Project

Welcome to the Data Warehouse and Analytics Project repository! 🚀This project showcases a comprehensive data warehousing and analytics solution, encompassing data architecture, ETL processes, and analytical reporting. Designed as a portfolio project, it adheres to industry best practices in data engineering and analytics.

📖 Project Overview

This project includes:

Data Architecture: Implementing a modern data warehouse using the Medallion Architecture with Bronze, Silver, and Gold layers.

ETL Pipelines: Extracting, transforming, and loading data from source systems into the warehouse.

Data Modeling: Structuring optimized fact and dimension tables for efficient analytical queries.

Analytics & Reporting: Developing SQL-based reports and dashboards to generate actionable insights.

🎯 This repository serves as a valuable resource for professionals and students aiming to demonstrate expertise in:

SQL Development

Data Architecture

Data Engineering

ETL Pipeline Development

Data Modeling

Data Analytics

🛠️ Tools & Resources

All resources are freely available:

Datasets: Access the project dataset (CSV files).

SQL Server Express: Lightweight database server.

SQL Server Management Studio (SSMS): GUI for database management.

GitHub: Version control and collaboration platform.

Draw.io: Tool for designing data architecture, models, and workflows.

Notion: Project management and documentation tool.

Notion Project Guide: Detailed project phases and tasks.

🚀 Project Requirements

Data Engineering: Building the Data Warehouse

Objective

Develop a modern SQL Server-based data warehouse to consolidate sales data, enabling analytical reporting and informed decision-making.

Key Features

Data Sources: Import sales data from two source systems (ERP & CRM) in CSV format.

Data Quality: Cleanse and resolve inconsistencies before analysis.

Integration: Merge data sources into a unified analytical model.

Scope: Focus on the latest dataset (historization not required).

Documentation: Provide detailed documentation for stakeholders and analysts.

Business Intelligence: Analytics & Reporting

Objective

Leverage SQL-based analytics to extract key insights into:

Customer Behavior

Product Performance

Sales Trends

These insights empower stakeholders to make data-driven strategic decisions.

For detailed specifications, refer to docs/requirements.md.

🏗️ Data Architecture

This project follows the Medallion Architecture, consisting of three layers:

Bronze Layer: Stores raw data ingested from CSV files into SQL Server.

Silver Layer: Cleansed and standardized data, prepared for analysis.

Gold Layer: Business-ready data modeled into a Star Schema for analytics.



📂 Repository Structure

data-warehouse-project/
│
├── datasets/                           # Raw ERP & CRM datasets
│
├── docs/                               # Documentation & architecture details
│   ├── etl.drawio                      # ETL process visualization
│   ├── data_architecture.drawio        # Project architecture diagram
│   ├── data_catalog.md                 # Dataset metadata & descriptions
│   ├── data_flow.drawio                # Data flow diagram
│   ├── data_models.drawio              # Star schema visualization
│   ├── naming-conventions.md           # Standardized naming guidelines
│
├── scripts/                            # SQL scripts for ETL & transformations
│   ├── bronze/                         # Extract & load scripts
│   ├── silver/                         # Data cleaning & transformation scripts
│   ├── gold/                           # Analytical model scripts
│
├── tests/                              # Data quality & validation tests
│
├── README.md                           # Project overview & instructions
├── LICENSE                             # License information
├── .gitignore                          # Git exclusions
└── requirements.txt                    # Dependencies & requirements

🛡️ License

This project is licensed under the MIT License. You are free to use, modify, and distribute it with proper attribution.

🌟 About Me

Hi! I'm Ibrahim Abdullahi Wushishi, Dedicated Data Analyst Team Lead with 6+ years of experience in the FMCG sector, specializing data analysis, Microsoft Excel, SAP, SAP Sales & Distribution, sales force development, sales support and administration, and sales operational optimization using tools like Power BI, SQL, and SAP ERP. Skilled in transforming complex data into actionable insights, driving sales performance, and enhancing business efficiency through innovative data-driven solutions..

Let's connect!

