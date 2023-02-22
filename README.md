# Building-Data-Pipelines-in-Azure-with-Azure-Synapse-Analytics
In this Microsoft Azure Data Engineering Project, I've build a data pipeline using Azure Synapse Analytics, 
Azure Storage and Azure Synapse SQL pool to perform data analysis on the 2021 Olympics dataset.

# Business Overview:

Data engineering is the profession of creating and constructing systems for gathering, storing, and analyzing large amounts of data. 
It is a vast field with applications in almost every sector.
In this project, I will be build a pipeline in Azure using Azure Synapse Analytics,
Azure Storage and Azure Synapse SQL pool to perform data analysis on the 2021 Olympics dataset. 

# Data Description:

For this project, I've working with the 2021 Olympics dataset.
This includes the information on more than 11,000 athletes competing in 47 sports for 743 Teams in the Tokyo Olympics in 2021. 
This dataset includes information on the participating Teams, Athletes, Coaches, and Entries by gender.
It includes their names, nationalities, sports they compete in, and name of coaches. The dataset contains 5 files as follows:

- Athletes file (Details about Athletes):

Name  
NOC  
Discipline  
 
- Coaches file (Details about coaches, countries and disciplines along with event):

Name  
NOC  
Discipline  
Event  
 
- EntriesGender file (Details about the Discipline and the number of females and males participating):

Discipline  
Male  
Female  
Total  

- Medals file (Contains the Medals and Scoreboard of countries that participated in Olympics):

Rank  
Team/NOC  
Gold  
Silver  
Bronze  
Total  
Rank by Total  

- Teams file (Details about the Teams, discipline, Name of Country and the event):

Name  
Discipline  
NOC  
Event  

# Tech Stack:

- Language: SQL

- Services: Azure Synapse Analytics, Azure Storage, Azure Synapse SQL Pool, Power BI

## Azure Synapse Analytics:

Azure Synapse is an unlimited analytics service that combines enterprise data warehousing and big data analytics. It gives you the freedom to query data on your terms, using serverless resources or being provisioned  at scale. Azure Synapse brings these two worlds together with a unified experience to ingest, prepare, manage, and deliver data for  BI and machine learning needs right out of the box.

## Azure Storage:

The Azure Storage platform is Microsoft's cloud storage solution for modern data storage scenarios. Azure Storage provides highly available, highly scalable, durable, and secure storage for a wide variety of data objects in the cloud.

## Azure Synapse SQL Pool:

Azure Synapse Analytics is an analytics service that unifies enterprise data warehouses and big data analytics.
Dedicated SQL pool refers to the enterprise data warehousing feature available in Azure Synapse Analytics. 
A dedicated SQL pool represents a collection of analytics resources provided when using Synapse SQL. 
The size of the dedicated SQL pool is determined by the data warehousing unit. 
Once a dedicated SQL pool is created, you can use simple PolyBase-T-SQL queries to import big data and
leverage the power of the distributed query engine to perform high performance analytics.

## Power BI:
Power BI is a collection of software services, apps, and connectors that work together to turn your unrelated sources of data into coherent,
visually immersive, and interactive insights. Your data might be an Excel spreadsheet, or a collection of cloud-based and on-premises hybrid data warehouses.
Power BI lets you easily connect to your data sources, visualize and discover what's important, and share that with anyone or everyone you want.

# Approach:

- Create an azure storage account and upload data files in a container.

- Create an azure synapse analytics workspace.

- Create a SQL pool in azure synapse workspace.

- Create table structure in SQL pool.

- Create a data pipeline to ingest data from azure storage into SQL pool tables.

- Load data from SQL pool tables into Power BI.

- Prepare dashboard in Power BI.

- Publish Power BI dashboard in Azure synapse workspace.

# Architecture Diagram
![image](https://user-images.githubusercontent.com/83840568/219877941-ccd0dc4b-48f1-484a-b710-0cae228e271d.png)


# Screenshots
## Creating Azure Resource Group, Azure Storage account and Azure Synapse workspace

![image](https://user-images.githubusercontent.com/83840568/219701737-c143eb7a-28d6-4d6e-a3f3-524a300168f7.png)
![image](https://user-images.githubusercontent.com/83840568/219702689-1fa80d8e-a0f0-47cd-b059-0026b831e347.png)
![image](https://user-images.githubusercontent.com/83840568/219702751-9136c442-429e-4c2c-a380-50dbac50bed0.png)
![image](https://user-images.githubusercontent.com/83840568/219702900-478b4b74-ceab-4d04-b6b3-c72126d344d6.png)

## Creating a SQL pool in Azure Synapse workspace,Creating tables in SQL pool
![image](https://user-images.githubusercontent.com/83840568/219704112-4aaaf2c4-70af-4323-ac1b-f55b553f738d.png)

## Create a pipeline to ingest data from Azure storage into SQL pool tables
![image](https://user-images.githubusercontent.com/83840568/219704276-d4aeb56b-a0e3-4188-9813-48e1d39e5535.png)

## Load data from Azure Synapse into Power BI, Creating visualizations in Power BI,Publishing Power BI dashboard
![image](https://user-images.githubusercontent.com/83840568/219704521-a69d4a65-aaa8-4a3b-b729-6724c41bc101.png)
![image](https://user-images.githubusercontent.com/83840568/219704741-2ee6c792-c471-4970-bc47-e38670a3bdab.png)
![image](https://user-images.githubusercontent.com/83840568/219704875-00e293ac-a430-4d31-aa06-74268123f148.png)
![image](https://user-images.githubusercontent.com/83840568/219705047-ca4b09b2-54f0-458a-a802-305c66ee0349.png)
![image](https://user-images.githubusercontent.com/83840568/219705229-4d420c66-b850-4057-b0ff-2fa59482b089.png)




