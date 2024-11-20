# End-to-End Azure Data Engineering Project

This repository showcases an end-to-end data engineering project leveraging Azure's ecosystem of tools and services. The project follows the Medallion Architecture to process and transform raw data into meaningful insights.

## Project Architecture

The project is structured into three layers based on the **Medallion Architecture**:
- **Bronze Layer**: Stores raw data ingested from the source (GitHub API).
- **Silver Layer**: Contains cleaned and transformed data.
- **Gold Layer**: Holds analytics-ready data for reporting and visualization.

## Tools and Technologies
- **Azure Data Factory**: For orchestration and data ingestion.
- **Azure Databricks**: For data transformation using Spark.
- **Azure Data Lake Gen2**: To store raw and transformed data.
- **Azure Synapse Analytics**: For building data models and queries.
- **Power BI**: For visualizing insights.
- **GitHub API**: As the data source.

## Features
- **Dynamic Pipelines**: Parameterized Azure Data Factory pipelines to handle multiple datasets.
- **Real-Time Scenarios**: Demonstrates practical use cases often encountered in real-world projects.
- **Scalable Design**: Handles large datasets and integrates seamlessly across Azure services.

## MIT License
Copyright (c) 2024 Free Licence
