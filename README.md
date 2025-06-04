# 🎬 Quality-Movie-Data-Analysis-Pipeline

This project demonstrates a serverless data pipeline to ingest only high-quality movie data into Amazon Redshift. It includes automatic schema detection, data quality checks, and transformation steps using low-code Glue ETL.

## 🚀 Tech Stack
- Amazon S3
- AWS Glue Crawler
- AWS Glue Catalog
- Glue Data Quality Ruleset
- AWS Glue Studio (Low-Code ETL)
- Amazon Redshift
- Amazon EventBridge
- Amazon SNS

## 📌 Features
- Automated schema detection and metadata cataloging with Glue Crawler
- Data quality validation using Glue Data Quality
- Low-code ETL job to transform and load valid data into Redshift
- Event-driven notifications via EventBridge and SNS for pipeline status

## 🏗️ Architecture
1. Raw movie data uploaded to S3
2. Glue Crawler updates the Glue Catalog
3. Data Quality rules evaluate dataset integrity
4. Glue ETL job transforms and loads clean data to Redshift
5. EventBridge triggers SNS alerts on job status

![Architecture](https://github.com/user-attachments/assets/7b349419-7f32-4fa7-95aa-f5965b479fef)


## SNS notification 
![image](https://github.com/user-attachments/assets/654701bb-33a5-4d9c-be2d-9aa743323ebb)
