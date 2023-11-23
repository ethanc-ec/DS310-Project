# CDS DS 310: Data Mechanics Final Project
Taught by [Professor Chris Seferlis](https://www.linkedin.com/in/cseferlis/), all text below is adapted from Seferlis' instructions.

## The Overall Task
- Your team will need to create a solution that extracts, cleans, loads, and analyzes this current data.​
- The solution needs to consider future use and expansion and be automated to run when new data is added and must kept and updated in source control.  ​

## Minor Tasks
- Create an enterprise Modern Data Pipeline solution that can be used for analysis and reporting by imaginary health and leadership officials​
- Make a recommendation on policies to implement as they compare to all policies​
- Document the solution business process and architecture​
- Write an executive summary of your analysis and findings (i.e. Why are you choosing the metrics you feel are most effective?)
- Put the solution under source control in GitHub so others can take over from where you left off

## Technical Learning Objectives
1. Create a team GitHub repository for Azure Data Factory
2. Provision a Data Lake
3. Land data in the Data Lake from Cloud resources (Azure SQL DB and CosmosDB).
4. Land data in the Data Lake from On-Premise resources (an Azure VM is used to simulate an on-prem store for SQL Server).
5. Create Data Pipelines to merge the datasets into useable format.
    - Use the .parquet format for all of your file output when pulling the data into your data lake for better storage efficiency.
6. Define Star Schemas and create a Data Warehouse.
7. Enact version control and administrative approval for all pull requests within Github.
8. Perform calculations on Fact tables.
9. Visualize the data with a compelling data story using Power BI
10. BONUS: Use some of the R and Python visuals in Power BI to model and predict what might happen in other circumstances. 
