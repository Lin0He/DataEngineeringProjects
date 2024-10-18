# DataEngineeringProjects

This project focuses on building an End-to-End Data Engineering pipeline for Real-Time Stock Market Data using Apache Kafka and Amazon Web Services (AWS). The pipeline involves:

Data Ingestion: Using Python to stream real-time stock market data as a producer, sending it to Kafka topics.
Infrastructure: Hosting Kafka on Amazon EC2 for streaming data between producer and consumer.
Data Processing: Utilizing AWS Glue for ETL (Extract, Transform, Load) processes and Athena for querying the data.
Storage and Querying: Storing the processed data in Amazon S3 and using SQL to analyze it through Athena.
