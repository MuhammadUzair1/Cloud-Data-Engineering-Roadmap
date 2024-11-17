# Cloud Data Engineering - Roadmap

Welcome to the **Cloud Data Engineering** course! This comprehensive 6-8 month journey is designed to equip you with the necessary skills to become a proficient Data Engineer, focusing on cloud-based technologies, data acquisition, modeling, warehousing, and orchestration. Our curriculum is divided into **5 modules** that include hands-on projects, assignments, and real-world case studies to ensure a practical understanding of the technologies covered.

---

This repository include the Roadmap for Data Engineering. Since Data Engineering is a broad field we'll try to cover following tools.

NOTE: It is a first draft of the course we'll Keep on updating.

**VERSION: 1.0.3**

---

## Table of Contents

1. [Course Overview](#course-overview)
2. [Module 1: Data Acquisition](#module-1-data-acquisition)
3. [Module 2: Data Modeling](#module-2-data-modeling)
4. [Module 3: Cloud Data Warehousing](#module-3-cloud-data-warehousing)
5. [Module 4: Data Orchestration & Streaming](#module-4-data-orchestration--streaming)
6. [Module 5: Architecting AWS Data Engineering Projects](#module-5-architecting-aws-data-engineering-projects)
7. [Why These Technologies?](#why-these-technologies)
8. [Final Notes](#final-notes)

---

## Course Overview

This course is meticulously crafted to cover all facets of Cloud Data Engineering. You'll learn everything from the basics of data acquisition and transformation to advanced cloud-based data warehousing, orchestration, and streaming techniques. The course is structured to build your skills progressively, ensuring you are ready to tackle complex data engineering challenges by the end.

- [Understanding Data Engineering](./docs/Understanding%20Data%20Engineering.pptx)

---

## Understanding Data Engineering

Before starting the digging deep into the field of Data Engineering one should know what is Data Engineering, What is the Scope of Data ENgineering in 2024, what tools are required to have knowledge for data engineering.

---

## Module 1: Data Acquisition

### Overview

The focus of this module is on acquiring, manipulating, and processing data from various sources. You'll set up your data engineering environment, explore Python for data manipulation, manage projects with version control, and gain hands-on experience with web scraping using BeautifulSoup and Selenium.

### Topics Covered

1. **Introduction to Data Engineering + Python Setup**

   - **Objective**: Understand the fundamentals of Data Engineering and Python setup.
   - **Outcome**: Be proficient in setting up Python and tools for data handling.

2. **Python for Data Engineering (Pandas) + Case Study**

   - **Objective**: Data manipulation using Pandas.
   - **Case Study**: Clean and analyze real-world datasets using Pandas.

3. **Version Control (Git + Python Project)**

   - **Objective**: Learn Git for version control and collaboration.
   - **Assignment**: Create a Python project and push it to GitHub.

4. **Bash/Shell Scripting**

   - **Objective**: Automate repetitive tasks using Shell scripts.
   - **Assignment**: Automate a data acquisition task using Bash.

5. **Web Scraping with BeautifulSoup**

   - **Objective**: Extract data from static websites.
   - **Assignment**: Scrape data from a webpage and save it in CSV/JSON format.

6. **Web Scraping with Selenium**

   - **Objective**: Scrape data from dynamic websites.
   - **Assignment**: Create a Selenium script to scrape data from an e-commerce site.

7. **Web Scraping Case Study**
   - **Final Assignment**: Build a comprehensive web scraping solution using both BeautifulSoup and Selenium.

---

## Module 2: Data Modeling

### Overview

Dive into database design, emphasizing efficient data storage, retrieval, and optimization. Learn SQL for data manipulation and advanced querying techniques.

### Topics Covered

1. **SQL Fundamentals with SQL Server**

   - Basic operations: `SELECT`, `WHERE`, `ORDER BY`
   - Data integrity using constraints

2. **Data Definition and Manipulation**

   - Create and alter database structures using DDL
   - Modify data within tables using DML

3. **Advanced Querying Techniques**

   - Aggregations, `GROUP BY`, and set operations like `UNION`, `INTERSECT`, `EXCEPT`
   - Use `CUBE` and `ROLLUP` for multidimensional analysis

4. **Joining Data**

   - Mastering `INNER`, `LEFT`, `RIGHT`, and `FULL OUTER` joins

5. **Performance and Structure**

   - Query optimization with indexes
   - Utilizing `VIEWS` and `SUBQUERIES`

6. **Advanced SQL Concepts**

   - Use Common Table Expressions (CTEs) and Window Functions

7. **Encapsulating Logic**
   - Writing `STORED PROCEDURES` and using `TRIGGERS`

---

## Module 3: Cloud Data Warehousing

### Overview

Master cloud-based data warehousing with Snowflake, focusing on scalability and handling large datasets. Gain hands-on experience through badge assignments and projects.

### Topics Covered

1. **Snowflake Overview**

   - Setting up your Snowflake environment

2. **Badges Assignment**

3. Batch 1: http://learn.snowflake.com/en/courses/uni-essdww101/
4. Batch 2: http://learn.snowflake.com/en/courses/uni-ess-cmcw/
5. Batch 3: http://learn.snowflake.com/en/courses/uni-ess-dabw/
6. Batch 4: http://learn.snowflake.com/en/courses/uni-ess-dlkw/
7. Batch 5: http://learn.snowflake.com/en/courses/uni-ess-dngw/

- [Project -2 Snowflake real time Data Warehouse for beginners](https://www.projectpro.io/project-use-case/snowflake-real-time-data-warehouse-project-for-beginners)
- [Project -3 Change Data Captue Pipeline with Snowflake & AWS ](https://www.projectpro.io/project-use-case/how-to-implement-slowly-changing-dimensions-in-snowflake)

3. **Snowflake Masterclass (Udemy)**

   - Working through 5 sections of the course to solidify understanding [Snowflake – The Complete Masterclass](https://www.udemy.com/course/snowflake-masterclass/)

4. **Hands-on Projects**
   - Implement 3 projects covering:
     - Data warehousing setup
     - ETL processes
     - Advanced querying and performance tuning

---

## Module 4: Data Orchestration & Streaming

### Overview

Explore data pipeline management with Apache Airflow and real-time data streaming with Apache Kafka.

### Topics Covered

**Airflow**

1. **Introduction to Apache Airflow**
   - Workflow automation using Airflow
2. **Classes & Project**
   - Build an Airflow project to automate data workflows

**Kafka**

1. **Introduction to Apache Kafka**
   - Real-time data streaming concepts
2. **Classes & Project**
   - Build a real-time data streaming project using Kafka

---

## Module 5: Architecting AWS Data Engineering Projects

### Overview

Dive deep into architecting data engineering solutions using AWS services. This module covers a wide range of tools from data storage, ETL, real-time data processing, to serverless computing.

### Topics Covered

1. **AWS Redshift**
   - Build and manage cloud-based data warehouses
2. **AWS S3**
   - Store and manage data efficiently
3. **AWS Glue & Athena**
   - Master ETL processes and querying
4. **AWS Lambda**
   - Automate workflows with serverless functions
5. **AWS EC2**
   - Manage compute resources for data processing
6. **AWS RDS**
   - Relational database management
7. **AWS Kinesis**
   - Real-time data streaming solutions

---

## Why These Technologies?

The technologies selected in this course are widely used in the data engineering industry. Python, SQL, Snowflake, Apache Airflow, and AWS are among the most in-demand skills, ensuring that you are job-ready by the end of this course. Each module builds upon the previous one, enabling you to apply theoretical knowledge to real-world projects.

---

## Final Notes

Throughout the course, you will engage in hands-on projects and assignments that simulate real-world data engineering tasks. This practical experience is crucial for mastering the skills required to excel in the field of Cloud Data Engineering.

Get ready to embark on this exciting journey of becoming a proficient Cloud Data Engineer! 🚀

---
