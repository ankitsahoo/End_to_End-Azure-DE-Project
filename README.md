# End_to_End-Azure-DE-Project | Azure Databricks | Azure Data Factory | Pyspark

**Project Architecure**
![Screenshot (69)](https://github.com/user-attachments/assets/54be829d-a46c-4b55-8caa-686b2c739f42)

**Workflow Diagram**
![Workflow](https://github.com/user-attachments/assets/835aa448-d8a1-44e4-b68b-765f8b561db6)

**Pipeline Execution**
![End to End Pipline(SQL-AzureDL)](https://github.com/user-attachments/assets/18579168-6abf-44e5-91a2-2758d938b67d)


An end-to-end Data Engineering project utilizing cutting-edge technologies like Azure Data Factory, Databricks, and PySpark. 
Covers the Unity Catalog for data governance.
Work with Delta Lake and Delta Tables for efficient data storage and processing.
Implement the Medallion architecture to structure your data pipeline effectively.
Encounter real-world scenarios such as Dimensional Data Modeling in Azure Databricks and Slowly Changing Dimensions in Databricks.

           +---------------------+
           |   Azure SQL Database |
           +---------------------+
                     |
        (Extract Data) |
                     v
           +-------------------+
           |  Azure Data Factory|
           |   (ETL Process)    |
           +-------------------+
                     |
     (Transform Data) | (Load Data)
                     v
           +---------------------------+
           | Azure Data Lake Storage   |
           |        Gen2                |
           +---------------------------+


Data Architecture (Medallion Architecture)
Data Ingestion Pipeline Design
Azure Project Overview
Data Understanding (API)
Azure Free Account
Azure Overview
Azure Data Lake
Creating Azure Resources
Azure SQL Server
Azure Data Factory 
Data Ingestion in Azure
Dynamic ETL Pipelines in Azure Data Factory
Incremental loading in Azure Data Factory
Azure Data Factory Real Time Scenarios
Azure Databricks
Unity Catalog Azure Databricks
Apache Spark Cluster
Access ADLS Gen2 from Databricks 
Data Transformation using PySpark
PySpark
Slowly Changing Dimensions using Pyspark
Star Schema Data Model (Fact Table)
Surrogate Keys in Data Warehouse
Databricks Workflows
End to End Azure Data Factory Pipeline
