# Creating-Streaming-Data-Pipeline-Using-Kafka

## Introduction
In this project, we are going to de-congest the traffic by analyzing the road traffic data from different toll gates. As a vehicle passes a toll, 
the vehicle’s data like **vehicle_id**, **vehicle_type**, **toll_plaza_id** and **timestamp** are streamed to Kafka. 

Our job is to create a end-to-end data pipe line that collects the streaming data using **kafka** and load it into a s3 bucket for furhter analysis using Athena.

## Objectives:
In this assignment we will create a streaming data pipeline by performing these steps:

- Install Kafka & Java in EC2 instance
- Start the Zoo-Keeper server
- Start the Kafka server
- Create a topic named **toll** in kafka.
- Create a streaming generator program [toll_traffic_generator_producer.ipynb](https://github.com/vekr1518/Creating-Streaming-Data-Pipeline-Using-Kafka/blob/main/toll_traffic_generator_producer.ipynb)
- Produce the topic **toll** data
- Consume the **toll** data using [toll_traffic_consumer.ipynb](https://github.com/vekr1518/Creating-Streaming-Data-Pipeline-Using-Kafka/blob/main/toll_traffic_consumer.ipynb)
- Load data to s3
- Create crawler to retrieve the data from s3 and create a table 
- Analyse the data using Athena

## Architecture
![This is an image](https://github.com/vekr1518/Creating-Streaming-Data-Pipeline-Using-Kafka/blob/main/Architecture.jpg)

## Technology Used
- Programming Language - Python
- Amazon Web Service (AWS)
  1. S3 (Simple Storage Service)
  2. Athena
  3. Glue Crawler
  4. Glue Catalog
  5. EC2
- Apache Kafka

## Dataset Used
We will be creating a real time traffic simulator data using python. 
