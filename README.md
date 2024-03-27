# Retail Store Modeling And Analysis Using DataStage
 
## Project Overview:

The project implements a star-schema data warehousing flow, then utilize IBM InfoSphere DataStage to develop efficient ETL (Extract, Transform, Load) pipelines to create data marts and perform some analysis on them.

The objective is to store and analyze data from a fictional retail store in a star-schema-based analysis data warehouse while ensuring all changes in the dimensions are preserved.

## Data Source:

The data source for populating the star schema.

![317454551-ef48039a-d9f2-40cd-bd2a-b83067a4131a](https://github.com/omarashrafhamdy/Retail-Store-Modeling-And-Analysis-Using-DataStage/assets/58981064/b5ef596c-18be-4f07-946e-0ba6757b4c12)

## Project Steps:

**1-Building Data Model:** Building star schema by using three dimensions: ```retail```,```customer```,```product``` and using ```transaction``` fact table.

![Modeling](https://github.com/omarashrafhamdy/Retail-Store-Modeling-And-Analysis-Using-DataStage/assets/58981064/8592bbfa-d63c-4e6e-ab42-49c297f80687)

**2-Extraction:** Extracting retail,customer,product data from the data warehouse

**3-Transformation:** Transforming on the data extracted to make customer name upper case

**4-Loading:** load the transformed data to a ```Retail Data Mart```

**5-Analysis:** Answering some business need by using Retail Data Mart:

- Display count of all transaction for each employee for each store
- Display max profit made by which customer type.Illustrate: customer type “foreign” make 5 transactions, customer type “citizen” makes 3 transactions.So, max profit made by foreign customers.Named DataMart “ACTIVATIONSALES_DATA_MART”
- Based on which customer make profit , give them Bouns Equation = Annual_Incomek$* SpendingScore*100

## Project Files:

- DataStage Jobs: Containing the dsx jobs used
- Dataset: The data that is used to make star schema model
- Output Files: The output for each job
- Screenshots: Screenshots for each job

## DataStage Jobs:

**Q1**
![Q1](https://github.com/omarashrafhamdy/Retail-Store-Modeling-And-Analysis-Using-DataStage/assets/58981064/e24af526-699e-4ae1-b0e8-fd5db496f28e)
**Q2**
![Q2](https://github.com/omarashrafhamdy/Retail-Store-Modeling-And-Analysis-Using-DataStage/assets/58981064/f422c2a2-24dd-45d9-9d73-299f476fdeb5)
**Q3 P1**
![Q3 P1](https://github.com/omarashrafhamdy/Retail-Store-Modeling-And-Analysis-Using-DataStage/assets/58981064/5190441c-a8d3-4628-b024-843785444ccb)
**Q3 P2**
![Q3 P2](https://github.com/omarashrafhamdy/Retail-Store-Modeling-And-Analysis-Using-DataStage/assets/58981064/c2ccf0f0-dc3c-4d3c-a744-83e2a8f16d19)
**Q3 In Only One Job**
![Q3 In One Job](https://github.com/omarashrafhamdy/Retail-Store-Modeling-And-Analysis-Using-DataStage/assets/58981064/a931e1e7-f2fd-4d2d-98f0-3e74fb71c656)

