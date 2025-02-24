# Azure-End-to-End-Project

# Data Pipeline Project Overview

- **Extract:** Retrieve raw data from GitHub-hosted CSV files using Azure Data Factory.
- **Store:** Save the raw data in Azure Data Lake Storage Gen2.
- **Transform & Clean:** Process the data with Apache Spark in Azure Databricks (e.g., remove duplicates, cast data types, aggregate insights).
- **Load:** Write the transformed data back to a separate folder in the Data Lake.
- **Enable Analysis:** Set up Azure Synapse Analytics to run SQL queries, supporting further visualization (with potential integration to tools like Power BI).

## Step-by-Step Process

### 1. Setting Up Azure Resources
- **Resource Creation:**  
  Set up the necessary Azure resources, including a storage account with ADLS Gen2 and creating resource groups.

### 2. Data Extraction with Azure Data Factory
- **Pipeline Development:**  
  Built a pipeline in Azure Data Factory that connected to the GitHub repository via HTTP.
- **Data Copy:**  
  Copied multiple CSV files (e.g., athletes, coaches, medals) from GitHub into the raw data folder in ADLS Gen2.

### 3. Data Transformation in Azure Databricks
- **Workspace Setup:**  
  Configured an Azure Databricks workspace and mounted the ADLS storage to access the raw data.
- **Data Processing:**  
  Wrote Apache Spark code to:
  - Remove duplicates.
  - Cast data types.
  - Perform aggregations.
- **Loading Transformed Data:**  
  Wrote the cleaned and transformed data back to a dedicated "transformed data" folder in ADLS Gen2.

### 4. Enabling Data Analysis with Azure Synapse Analytics
- **Integration:**  
  Integrated Azure Synapse Analytics to query the transformed data.
- **Analysis:**  
  Enabled detailed analysis by running SQL queries, which supports visualization efforts (e.g., integration with Power BI).

## Project Results

- **Fully Functional Pipeline:**  
  Delivered a scalable data pipeline that seamlessly moved data from extraction through transformation to analysis.
- **Demonstrated Proficiency:**  
  Showcased expertise with key Azure services including Data Factory, Data Lake Storage Gen2, Databricks, and Synapse Analytics.
- **Improved Efficiency & Insights:**  
  Enhanced data processing efficiency and provided reliable insights on Olympic performance metrics.
- **Value Addition:**  
  Added significant value to the overall data analytics strategy by enabling robust, real-time data analysis.
