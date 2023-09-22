
# Azure Data Factory and Databricks

This project aims to implement Analytics/Insights on the flight delay data from SQL Server, utilizing a combination of Azure Data Factory (ADF), Azure Blob Storage (ADLS Gen2), and Azure Databricks, in accordance with a Medallion Architecture approach. The project entails data ingestion into a Bronze Zone, data transformation through Azure Databricks, and data loading into Delta tables for the Gold Zone. Moreover, we have created a pipeline and scheduled it using Azure Data Factory and leveraged Logic Apps for pipeline resiliency in order to trigger emails.

