---
title: Creating a Free Azure SQL Database (SQL Server Database)
date: 2020-06-25T17:03:38.866Z
last_modified_at: 2020-06-27T14:51:00.898Z
tags:
  - "# Azure"
comments: true
---
In this post, we go through how to create a free Azure SQL Database.

[Azure SQL Database](https://docs.microsoft.com/en-us/azure/azure-sql/database/sql-database-paas-overview) runs on the stable version of Microsoft SQL Server database engine. If we follow the Microsoft Docs [tutorial](https://docs.microsoft.com/en-us/azure/azure-sql/database/single-database-create-quickstart?tabs=azure-portal) on how to create an Azure SQL Database, there is no free tier available. The least tier is basic with approximately $5 US Dollar per month.

![Basic tier SQL Database Pricing](/assets/images/uploads/2020-06-25-pricing.png)

There is a little workaround here. We have to create a combo of **Web App + SQL** to get a free database. Then, delete the Web App (because it is not needed), after that you can use database.

## Steps to create free database:

**step 1:**

1. Go to [Azure Portal](https://portal.azure.com/) and click on **create a resource** icon. Search for `Web App + SQL`.

   ![Web App + SQL](/assets/images/uploads/2020-06-25-search-database.png)

   Click on create button to create **Web App + SQL** resource.

   ![create Web App + SQL](/assets/images/uploads/2020-06-25-create.png)


2. In **Web App + SQL create** Page, fill all the data that is required.

   If you click on `SQL Database` you can create a new database or select existing databases. In our case we create a new database. Before creating database configure `Target Server` settings for database.



   ![Web App + SQL data entry](/assets/images/uploads/2020-06-25-data-entry-database.png)



## Limitations of free database

The maximum size of database is **32 MB of shared storage and 5 DTUs .**

This database is a trial for one year and after a year it gets upgraded to **Basic** tier.

This database is useful for learning and testing purposes only as it has low storage.