# real-time-streaming-databricks-azure-event-hub

This project explores Azure EventHubs as a data source to be consumed within Databricks and a dashboard set up in PowerBI

# Azure Event Hubs

Azure Event Hubs is a fully managed, real-time data ingestion service that is simple, trusted, and scalable. It can stream millions of events per second from any source to build dynamic data pipelines and immediately respond to business challenges. EventHubs can process and store events, data, or telemetry produced by distributed software and devices. It is ideal for applications such as logging, telemetry, fraud detection, and live dashboarding.

We use this service to simulate data events generation

# Databricks

Databricks is built on top of the Data Lakehouse and acts as a unified data analytics platform to process multiple different kinds of data that appear in the lakehouse, which combines features of the data warehouse and the data lake. Combined with the Unity Catalog, the Databricks platform allows end-to-end governance and usage of multiple accounts on multiple forms of data, multiple functions including ML models etc. Data is typically stored in the Medallion format (bronze -> raw ingested data with some extra auditing fields, silver -> transformations and joins to represent rudimentary business logic and prepare it in structure for basic business intelligence, gold -> aggregates representing finer business intelligence).
