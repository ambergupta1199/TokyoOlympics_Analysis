### Architecture Diagram
![image](https://github.com/ambergupta1199/TokyoOlympics_Analysis/assets/79975210/3213ab0f-1b45-4438-ada5-ad29b74db744)
### Project Architeccture Explanation
- **Data ingestion process**: Ingested raw data from Github using HTTP method in Azure Data factory and then dumped data into ADLS Gen 2 storage account.
- **Transformation**: Transformed the data in Azure Databricks using Pyspark & then dumped transformed cleaned data into ADLS Gen 2 storage account.
- **Implementation of Business Logic:** Implemented Logic in Azure Synapse using SQL.
- **Analyzing the data:**: Created Synapse endpoint in Power BI to fetch the transformed data & created report on top of it.
### Power BI visualization dashboard
![image](https://github.com/ambergupta1199/TokyoOlympics_Analysis/assets/79975210/01e8d20f-7776-414a-8439-519b462311e1)

