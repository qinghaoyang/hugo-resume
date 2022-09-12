---
title: "3. Batch and Stream processing for a dataset from the US Department of Transportation"
link: "https://drive.google.com/file/d/11jIUE7EynYpGXIzScaD_ZVNw-kVnfuLZ/view?usp=sharing"
image: "/img/pipeline.png"
video: ""
description: "<li> Extracted and cleaned the dataset, stored around 0.3 billion records into HDFS on a cluster of 5 nodes created by Amazon EMR. Built a pipeline with Spark for processing data in batches and storing data into DynamoDB. <li> Built a stream processing system including AWS Lambda responding to events, a Kafka cluster with 3 brokers and 100 partitions ingesting data produced by AWS Lambda, and Spark Streaming processing data from Kafka, achieving around 65MB/s throughput."
featured: true
tags: ["AWS","Spark","Kafka"]
fact: ""
weight: 100
sitemap: 
    priority : 0.8
---
