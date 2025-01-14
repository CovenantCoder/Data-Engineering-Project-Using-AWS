# Data-Engineering-Project-Using-AWS
AWS-Powered YouTube Data Pipeline for Scalable Analysis and Reporting

## Overview
This project focuses on securely managing, optimizing, and analyzing structured and semi-structured YouTube video data, with a focus on video categories and trending metrics.

## Project Goals:

1. Data Ingestion — Develop a system to gather data from various sources.
2. ETL System — Transform raw data into a structured format suitable for analysis.
3. Data Lake — Store data from multiple sources in a centralized repository for easy access.
4. Scalability — Ensure the system can scale to accommodate the growing volume of data.
5. Cloud — Leverage cloud infrastructure, specifically AWS, to process large datasets beyond local computing capabilities.
6. Reporting — Create an interactive dashboard to answer key business questions based on the data analysis.

## Services We Have Used:

- Amazon S3: We have used Amazon S3 for object storage, providing scalability, data availability, security, and performance to manage large datasets efficiently.

- AWS IAM: We have used AWS Identity and Access Management (IAM) to securely manage and control access to AWS services and resources, ensuring proper permissions and security.

- AWS Glue: We have used AWS Glue as a serverless data integration service to simplify the discovery, preparation, and transformation of data for analytics, machine learning, and application development.

- AWS Lambda: We have used AWS Lambda for serverless computing, allowing us to run code without managing or provisioning servers, facilitating automated data processing.

- Amazon Athena: We have used Amazon Athena to query data directly stored in Amazon S3 using SQL, enabling us to analyze data efficiently without needing to load it into a separate database.

- Amazon QuickSight: We have used Amazon QuickSight for scalable, serverless business intelligence, enabling us to create interactive visualizations and insights with machine learning-powered analytics.


## Dataset Used
This dataset from Kaggle provides statistics (in CSV format) on daily trending YouTube videos over several months. It includes data for up to 200 popular videos published each day across various regions, with each region's data stored in a separate file. The dataset contains information such as the video title, channel title, publication time, tags, views, likes, dislikes, description, and comment count. Additionally, a category_id field, which varies by region, is included in the corresponding JSON file for each location.
https://www.kaggle.com/datasets/datasnaek/youtube-new

## Architecture Diagram
<img src="architecture.jpeg">
