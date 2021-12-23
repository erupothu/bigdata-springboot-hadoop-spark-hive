# bigdata-springboot-hadoop-spark-hive
Big Data and ETLs

#### Big Data Ingestion Layer
* This layer of Big Data Architecture is the first step for the data coming from variable sources to start its journey. Data ingestion means the data is prioritized and categorized, making data flow smoothly in further layers in the Data ingestion process flow.
 * Databases:
  * MySQL:
  * Postgres:
  * HBase
  * MongoDB
  * CSV, XLSX, Text


#### Data Collector Layer
* In this Layer, more focus is on the transportation of data from the ingestion layer to the rest of the data pipeline. It is the Layer of data architecture where components are decoupled so that analytic capabilities may begin.
  * __Query Tools__: 
    * __Apache Hive__: Apache Hive is a data warehouse infrastructure built on top of Apache Hadoop for providing data summarization, ad-hoc query, and analysis of large datasets.
    * __Apache Spark SQL__: Spark SQL includes a cost-based optimizer, columnar storage, and code generation to make queries fast.
    * __Amazon Redshift__: Amazon Redshift is a fully managed, petabyte-scale data warehouse service in the cloud. We use Amazon Redshift to load the data and run queries on the data. We can also create additional databases as needed by running an SQL command. Most important, we can scale it from a hundred gigabytes of data to a petabyte or more.
    * __Presto__: Presto is an open-source distributed SQL query engine for running interactive analytic queries against data sources of all sizes ranging from gigabytes to petabytes.

#### Data Processing Layer
* In this primary layer of Big Data Architecture, the focus is to specialize in the data pipeline processing system. We can say the data we have collected in the previous layer is processed in this layer. Here we do some magic with the data to route them to a different destination and classify the data flow, and it’s the first point where the analytic may occur.
 * __Big Data Processing Tools__:
  * __Apache Sqoop__
    * It efficiently transfers bulk data between Apache Hadoop and structured datastores such as relational databases. Apache Sqoop can also extract data from Hadoop and export it into external structured data stores.
  * __Apache Storm__
    * It is a system for processing streaming data in real-time during Data ingestion. It adds reliable real-time data processing capabilities to Enterprise Hadoop. Storm on YARN is powerful for scenarios requiring real-time analytics, machine learning, and continuous monitoring of operations.
  * __Apache Spark__
    * Apache Spark Optimization is a fast, in-memory data processing engine with elegant and expressive development APIs to allow data workers to efficiently execute streaming, machine learning, or SQL workloads that require fast iterative access to data sets.
  * __Apache Flink__
    * Apache Flink is an open-source framework in the Data ingestion pipeline for distributed stream processing that provides accurate results, even in out-of-order or late-arriving data or Distributed Data Processing Apache Flink.

#### Data Storage Layer
* Storage becomes a challenge when the size of the data you are dealing with becomes large. Several possible solutions, like Data Ingestion Patterns, can rescue from such problems. Finding a storage solution is very much important when the size of your data becomes large. This layer of Big Data Architecture focuses on “where to store such large data efficiently.”
  * __Storage Tools__:
    * __HDFS__: Hadoop Distributed File System: HDFS is a Java file system that provides scalable and reliable data storage, and it helped to span large clusters of commodity servers.
    * __GlusterFS__: Dependable Distributed File System: GlusterFS are suitable for unstructured data such as documents, images, audio and video files, and log files. GlusterFS is a scalable network filesystem. Using this, we can create large, distributed storage solutions for media streaming, data analysis, data ingestion, and other data- and bandwidth-intensive tasks.
    * __Amazon S3 Storage Service__: Amazon Simple Storage Service (Amazon S3) is object storage with a simple web service interface to store and retrieve any data from anywhere on the internet.

#### Data Visualization Layer
* The visualization, or presentation tier, probably the most prestigious tier, where the data pipeline users may feel the VALUE of DATA. We need something that will grab people’s attention, pull them into, make your findings well-understood.
  * __Visualization Tools__:
    * __Tableau__: Tableau is the richest data visualization tool available in the market, with Drag and Drop functionality.
    * __Kibana__: A Kibana dashboard displays a collection of saved visualizations. You can arrange and resize the visualizations according to requirements and save dashboards, to reload and share.
    * __Intelligence Agents__: An intelligent agent is a software that assists people and acts on their behalf. Intelligent agents work by allowing people to delegate work they could have done to the agent software. Agents can perform repetitive tasks, remember things you forgot, intelligently summarize complex data, learn from you, and even make recommendations.

#### Big Data Ingestion Layer
* Data ingestion mystery can be well understood using the Layered Architecture of Big Data. The Layered Architecture of the Big Data ingestion pipeline is divided into different layers, where each layer performs a particular function.

#### Editing Tool
* __zeppelin__
* __Jyputer__
* __spark-notebook__

