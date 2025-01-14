# Data-Engineering-Project-Using-AWS
AWS-Powered YouTube Data Pipeline for Scalable Analysis and Reporting

## Overview
This project focuses on securely managing, optimizing, and analyzing structured and semi-structured YouTube video data, with a focus on video categories and trending metrics.

## Project Goals
1. Data Ingestion — First, we built a robust mechanism to ingest data from multiple sources, ensuring that daily trending YouTube video data was consistently collected across different regions.

2. ETL System — After data ingestion, we implemented an ETL system that transformed the raw data into a structured format, cleaning and organizing it for further analysis and reporting.

3. Data Lake — Following the transformation, we established a centralized data repository in Amazon S3 to securely store the ingested and processed data, making it easily accessible for future analysis.

4. Scalability — To accommodate the growing volume of data, we ensured the system was scalable by utilizing AWS services, allowing it to efficiently handle increased data loads without compromising performance.

5. Cloud — Given the large scale of the data, we leveraged AWS cloud infrastructure to process and analyze the data, taking full advantage of its high-performance capabilities and eliminating the limitations of local computing.

6. Reporting — Finally, we created interactive dashboards using Amazon QuickSight, enabling stakeholders to visualize and analyze key metrics from the YouTube data, providing insights into video performance, user engagement, and trends.

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


