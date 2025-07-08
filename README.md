# End-to-End Data Engineering Project on Databricks

This project demonstrates a complete end-to-end data engineering pipeline built entirely on the Databricks platform. It shows how to ingest data from a public REST API, transform it using Apache Spark.

## Project Overview
 Extracting data from news API, transforming it, and moving the data to a database on Databricks workspace, and also automate this job to run.
- **Data Ingestion:** Fetch JSON data from the public API endpoint directly into Databricks using Spark.
- **Data Exploration:** Inspect the data schema and preview contents using Spark DataFrame API and SQL.
- **Data Transformation:** Clean and prepare the data by flattening nested structures, selecting relevant columns, and renaming them for clarity.
- **Automation:** Schedule the job to run periodically for continuous data ingestion and updates.

## Technologies Used

- Azure Databricks
- Apache Spark (PySpark)
- REST API (JSON data source)
