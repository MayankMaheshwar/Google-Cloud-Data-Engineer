# Google-Cloud-Data-Engineer

This project is about building several Data Pipelines that ingest data from a publicly available dataset into BigQuery, using these Google Cloud services:

Cloud Storage Dataflow BigQuery


Components used- 
TextIO - Read and write and text files
Apache beam - open source unified programming model to define and execute data processing pipelines, including ETL, batch and stream processing


why using dataflow instead of dataproc-

Cloud Dataproc provides you with a Hadoop cluster, on GCP, and access to Hadoop-ecosystem tools (e.g. Apache Pig, Hive, and Spark); this has strong appeal if you are already familiar with Hadoop tools and have Hadoop jobs
Cloud Dataflow provides you with a place to run Apache Beam based jobs, on GCP, and you do not need to address common aspects of running jobs on a cluster (e.g. Balancing work, or Scaling the number of workers for a job; by default, this is automatically managed for you, and applies to both batch and streaming) -- this can be very time consuming on other systems
