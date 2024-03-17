### Architecture Diagram
![image](https://github.com/ambergupta1199/TokyoOlympics_Analysis/assets/79975210/3213ab0f-1b45-4438-ada5-ad29b74db744)
### Project Architeccture Explanation
- **Data ingestion process**: Ingested raw data from Github using HTTP method in Azure Data factory and then dumped data into ADLS Gen 2 storage account.
- **Transformation**: Transformed the data in Azure Databricks using Pyspark & then dumped transformed cleaned data into ADLS Gen 2 storage account.
- **Implementation of Business Logic:** Implemented Logic in Azure Synapse using SQL after loading data into Synapse from ADLS
- **Analyzing the data:**: Created Synapse endpoint in Power BI to fetch the transformed data & created report on top of it.
### Power BI visualization dashboard
![image](https://github.com/ambergupta1199/TokyoOlympics_Analysis/assets/79975210/01e8d20f-7776-414a-8439-519b462311e1)
## Project Snapshots
- **Data ingestion**
![image](https://github.com/ambergupta1199/TokyoOlympics_Analysis/assets/79975210/916ceb2c-d79a-4769-a20e-d6b786aacdfc)
- **Dumped raw data to ADLS**
![image](https://github.com/ambergupta1199/TokyoOlympics_Analysis/assets/79975210/49b982f2-3112-4442-8f10-4a62742edcb9)
- **Transformed data in Azure Databricks**
  ![image](https://github.com/ambergupta1199/TokyoOlympics_Analysis/assets/79975210/c62ff59a-f3a1-475b-9d76-583a246be304)
- **Dumped Transformed data in ADLS**
  ![image](https://github.com/ambergupta1199/TokyoOlympics_Analysis/assets/79975210/3b3fb001-ae77-4257-b1e8-fd44c8ad7e27)
  






