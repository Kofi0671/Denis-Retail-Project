# Denis-Retail-Project
Cloud Migration for Denis Retail Dataset Using Azure Data Factory

Introduction
The digital landscape in recent times, transitioning from traditional on-premises databases to cloud platforms is essential for achieving scalability, improved reliability, and enhanced analytical capabilities. This article focusses on creating cloud data migration content as a detailed guide on how to any organization can migrate their data just like the Denis retail dataset from an on-premises MySQL database to Azure SQL Database by leveraging Azure Data Factory (ADF).

Architecture Overview
The diagram below illustrates the overall data migration flow using Azure Data Factory as the central orchestration tool.



Step-by-Step Migration with ADF
•	1. Install Integration Runtime: Deploy and configure the Self-hosted Integration Runtime on the local MySQL server to enable secure data movement.
•	2. Configure Linked Services: Set up connections within ADF for both the source (on-prem MySQL) and the destination (Azure SQL Database).
•	3. Define Datasets: Create datasets in ADF to represent the structure of the source and target tables within the Denis retail schema.
•	4. Develop ETL Pipelines: Design data pipelines in ADF to handle extraction, transformation, and loading (ETL) processes between environments.
•	5. Scheduling and Monitoring: Use ADF’s built-in features to automate pipeline execution and monitor activity in real-time.


Dataset Overview: Denis Retail
I want to share my experience of The Denis retail dataset including core business tables such as Products, Sales, Customers, and Transactions. Each table is migrated using ADF’s Copy Activity, which allows for schema alignment and data consistency between the source and destination.

Conclusion
Let me conclude by saying Azure Data Factory streamlines the transition of data from on-prem systems to the cloud. I was able to implement this migration strategy, organizations can reap the benefits of cloud computing, including scalability, real-time access, and advanced data analysis, including cost control by pay for what you consumed.


![image](https://github.com/user-attachments/assets/a23edd62-78c9-446b-a349-2bdbabd570a7)


