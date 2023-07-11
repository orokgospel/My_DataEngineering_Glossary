# My_DataEngineering_Glossary
The purpose of this Data Engineering Glossary is to provide a knowledge and tool box specifically designed for data engineering. Its aim is to assist with data engineering tasks, jobs, and comprehension of the essential concepts, principles, and workflow involved in solving problems within the field of data engineering.


# **Data Engineering Project Overview**
# Tools and Technologies:
* OLTP database - MySQL
* NoSql database - MongoDB
* Production Data warehouse – DB2 on Cloud
* Staging Data warehouse – PostgreSQL
* Big data platform - Hadoop
* Big data analytics platform – Spark
* Business Intelligence Dashboard - IBM Cognos Analytics
* Data Pipelines - Apache Airflow

# Job Task and Process:

- **SoftCart's** online presence is primarily through its website, which customers access using a variety of devices like laptops, mobiles and tablets.

- All the **catalog data** of the products is stored in the **MongoDB NoSQL server**.

- All the **transactional data** like inventory and sales are stored in the **MySQL database server**.

- **SoftCart's** webserver is driven entirely by these **two databases**.

- Data is periodically extracted from these two databases and put into the **staging data warehouse** running on **PostgreSQL.**

- The production **data warehouse** is on the cloud instance of **IBM DB2 server.**

- **BI teams** connect to the IBM DB2 for operational dashboard creation. **IBM Cognos Analytics** is used to create **dashboards.**

- SoftCart uses **Hadoop cluster** as its big data platform where all the data is collected for analytics purposes.

- **Spark** is used to analyse the data on the Hadoop cluster.

- To move data between OLTP, NoSQL and the data warehouse, **ETL pipelines are used and these run on Apache Airflow.**
