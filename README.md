# Olympic Data Analytics | Azure End-To-End Data Engineering Project

## Introduction

To gain hands-on experience with Microsoft Azure's cloud services by analyzing and extracting insights from the Tokyo Olympics dataset. The project aimed to leverage various Azure services to implement a full-scale data analytics pipeline, from data ingestion to visualization.

## Architecture

![](images/ArchitectureOf_DataAnalysis_WorkFlow.drawio.png)

### Data Acquisition

I obtained datasets from Kaggle 📈 and implemented data integration pipelines using Azure Data Factory 🔄 to facilitate efficient data movement and transformation (ETL) between various sources and destinations within Azure and beyond.

#### Data Integration & ETL Process
Azure Data Factory (ADF)

Purpose: Implemented for orchestrating data pipelines that manage the movement and transformation of data across different platforms.

Process: Set up and automated data pipelines that handled Extract, Transform, Load (ETL) processes, ensuring efficient data integration
between various sources (e.g., Azure Blob Storage, on-premises databases) and destinations (e.g., Azure Data Lake, Azure SQL Database).

Outcomes: Facilitated seamless data flow, ensuring that data from the Tokyo Olympics was accurately transformed and stored for further processing.

#### Data Storage

Azure Data Lake Storage Gen2

Purpose: Used for storing the large datasets securely while enabling high-performance analytics.
Features : Leveraged its hierarchical namespace to organize data and utilized advanced security features like Azure Active Directory integration for access control.



