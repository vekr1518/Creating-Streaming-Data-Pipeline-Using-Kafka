# Creating-Streaming-Data-Pipeline-Using-Kafka

## Introduction
In this project, we are going to de-congest the traffic data by analyzing the road traffic data from different toll gates. As a vehicle passes a toll, 
the vehicle’s data like **vehicle_id**, **vehicle_type**, **toll_plaza_id** and **timestamp** are streamed to Kafka. 

Our job is to create a end-to-end data pipe line that collects the streaming data using **kafka** and load it into a s3.

## Architecture
![This is an image](https://myoctocat.com/assets/images/base-octocat.svg)

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
