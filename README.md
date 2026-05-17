# End-to-End-Data-Pipeline-on-AWS-S3-Lambda-Glue-QuickSight-Hands-on
First AWS Project
- Project Title & Description
- Demo GIF or Screenshots
- Architecture Diagramr
- Tech Stack Used
- AWS Services Used (even after they're gone)
- Setup Instructions
- YouTube/Tutorial Reference
- What I Learned
- Live Demo Link (while active)

we build a fully automated, serverless data pipeline on AWS. We’ll take raw CSV data from an S3 bucket and transform it into a professional business intelligence dashboard using AWS Lambda, Glue, and QuickSight. Whether you are an aspiring Data Engineer or a Cloud Architect, this project will help you master the "glue" that holds modern data platforms together.

# What You Will Learn:

S3: Setting up landing zones for raw data.
AWS Lambda: Triggering automated workflows on file upload.
AWS Glue: Running Crawlers and ETL jobs to catalog your data.
Amazon Athena (Optional/Mentioned): Querying data using SQL.
Amazon QuickSight: Building interactive visualisations.

# Project Overview
This Project involves building a serverless data pipeline on AWS for processing CSV files. The pipeline automates the ingestion, transformation, and visualization of data. CSV files are uploaded to an raw data S3 bucket (csv-raw-data), triggering an AWS Lambda function to preprocess the data and store it in the processed data bucket(csv-processed-data).

AWS Glue is then used for further ETL (Extract, transform, Load) operations, and the final data is stored in final data bucket (csv-final-data). Finally, Amazon QuickSight is used to create interactive dashboards and reports for visualizing the final data.
