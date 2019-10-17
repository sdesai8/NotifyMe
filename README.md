# NotifyMe
A Data Warehouse Notification System

# Table of Contents
1. [Background](README.md#background)
1. [Project Overview](README.md#project-ovreview)
1. [Data Source](README.md#data-source)
1. [Tools and technologies used](README.md#tools-and-technologies-used)
1. [Flow of Data](README.md#flow-of-data)
1. [Cluster Structure](README.md#cluster-structure)
1. [Repo Directory Structure](README.md#repo-directory-structure)
1. [Presentation Slides](README.md#presentation-slides)
1. [Contacts](README.md#contacts)

# Background
Gathering the relavant datasets from variuos data sources for your data start up/articles/projects can be time consuming and tedious process. Especially datasets change so frequently, it does add extra burden on data scientists/analysts to iterate the same process again and again. It was very important to buid the unified, centralized and one click away data warehouse system to address above issues with added facility of subscription based notification system.

# Project Overview
This project facilitates a plaform for Data Scientists/Analysts, Journalists, and Startup Enthusiasts to access various data sources at one stop, unified, centralized data warehouse. With facility of email notification when there is any changes in datasets the users have subscribed to.

# Data Source
Dataset was crafted by scraping the DATA.GOV website which has various (14) categories of data such as agriculture, finance, education, healthcare in different formats as csv, json, pdf, html, zip, rdf, jpeg etc, total ups as 2TB. 

# Tools and technologies used
1. AWS EC2
2. Apache Spark
3. AWS Redshift
4. Apache Airflow
5. AWS SNS(Simple Notification System)
6. Beautifulsoup
7. AWS S3

# Flow of Data

# Cluster Structure
1. Web-scrapping: 1 EC2 m4.xlarge 
2. Spark Cluster: 4 EC2 m4.xlarge [Installation](https://blog.insightdatascience.com/simply-install-spark-cluster-mode-341843a52b88)
3. Redshift Cluster: 3 DC2.large [Installation](https://docs.aws.amazon.com/redshift/latest/gsg/getting-started.html)
4. Airflow: 1 EC2 m4.xlarge [Installation](https://blog.insightdatascience.com/scheduling-spark-jobs-with-airflow-4c66f3144660)

# Repo Directory Structure

# Presentation Slides
[Slides](https://tiny.cc/jc3mez)

# Contacts
Questions? Please feel free to connect over email (savandesai095@gmail.com)
Thank you,
Savankumar Desai
