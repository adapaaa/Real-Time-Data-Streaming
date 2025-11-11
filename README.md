# Real-Time-Data-Streaming
This project covers each stage from data ingestion to processing and finally to storage, utilizing a robust tech stack that includes Apache Airflow, Python, Apache Kafka, Apache Zookeeper, Apache Spark, and Cassandra. Everything is containerized using Docker for ease of deployment and scalability.

# System Architecture
<img width="3274" height="1221" alt="Data engineering architecture" src="https://github.com/user-attachments/assets/0b15c74d-168c-4610-9226-dcdabcedd953" />

# The project is designed with the following components:

**Data Source**: We use randomuser.me API to generate random user data for our pipeline.

**Apache Airflow**: Responsible for orchestrating the pipeline and storing fetched data in a PostgreSQL database.

**Apache Kafka and Zookeeper** : Used for streaming data from PostgreSQL to the processing engine.

**Control Center and Schema Registry**: Helps in monitoring and schema management of our Kafka streams.

**Apache Spark**: For data processing with its master and worker nodes.

**Cassandra**: Where the processed data will be stored.

# Technologies:
Apache Airflow

Python

Apache Kafka

Apache Zookeeper

Apache Spark

Cassandra

PostgreSQL
Docker
