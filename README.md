# MSBX 5420 - Spring 2020
# Unstructured and Distributed Data Modeling and Analysis

Leeds School of Business, University of Colorado Boulder


## Contact Information

**Instructor:**  
- Dr. Peigang(Peter) Zhang (peigang.zhang@colorado.edu)

**Office hours:**  
- Thursday 7pm - 9pm, KOBL 219. You can join office hour by Zoom - https://cuboulder.zoom.us/j/2718416002

## Course Description

In this course we will study how to store, process, and extract insights from unstructured data.
For us, unstructured data is any data that cannot be directly queried using SQL.  It arises in several situations:

- The data has simply not been loaded into a relational database yet.
- The data is too big to be loaded into a traditional relational database.
- The data might not naturally make sense in the SQL paradigm (e.g. images, emails, videos).

The main problem is to figure out how to process unstructured data at large scale.
We will learn how to distribute large datasets across dozens, hundreds, or even thousands of machines.  This is “Big Data”.

In particular, we will study the following:

- How to store large datasets in the **Hdfs** filesystem (part of the **Hadoop** family of technologies).
- How to process large datasets using **Spark** (a glorified task scheduler).
- How to store streaming data in **Kafka**, a modern message queueing system.
- How to consume messages from Kafka and analyze them in near-realtime using **Spark Streaming**.
- How to query large datasets with so-called “NoSQL” datastores such as **Elasticsearch** and **Cassandra**.
- How to use cloud computing infrastructure such as **AWS** to process and analyze big data.


## Course Objectives

By the end of this course students should be able to:

- Use standard software development tools such as the Linux command line (`bash`), `git`, GitHub, and `docker`.
- Store and manipulate files in HDFS.
- Write `pyspark` scripts from within a python notebook (`jupyter`), and perform analysis to extract insights.
- Consume streaming messages from Kafka, and join/enrich streaming data using `ksql`
- Stream data into NoSQL datastores such as Elasticsearch or Cassandra, and visualize using Kibana.
- Use AWS to process and analyze big data.
