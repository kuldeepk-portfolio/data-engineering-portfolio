# Data Engineering Portfolio

Welcome to my Data Engineering Portfolio. I’m **Kuldeep Kumar**, a data-focused engineer with a strong background in SQL, Python, cloud infrastructure, and automation. This repository showcases a curated collection of end-to-end data engineering projects designed to demonstrate my expertise in building scalable, production-ready data pipelines across various technologies and platforms.

Each project is structured to reflect real-world data engineering scenarios, including data ingestion, transformation, storage, orchestration, and deployment in cloud environments.

---

## 🚀 Key Skills Demonstrated

- Batch and streaming data pipelines
- Data modeling (relational + NoSQL)
- Cloud-native architecture (AWS)
- ETL/ELT with Python, Spark, Pandas
- Data orchestration with Apache Airflow
- Real-time processing using Apache Kafka
- Infrastructure automation with Terraform & Shell

---

## 📁 Project Index

| Project Name | Tech Stack | Description |
|--------------|------------|-------------|
| [`pandas-postgres-etl`](./pandas-postgres-etl) | Python, Pandas, PostgreSQL | Ingest, clean, and load customer data into a relational database |
| [`spark-nyc-taxi-pipeline`](./spark-nyc-taxi-pipeline) | PySpark, AWS S3 | Batch ETL pipeline on large-scale NYC Taxi dataset |
| [`kafka-log-streaming`](./kafka-log-streaming) | Kafka, Spark Structured Streaming | Real-time streaming and processing of application logs |
| [`airflow-sales-dag`](./airflow-sales-dag) | Apache Airflow, S3, Redshift | Orchestration of daily sales ETL pipeline |
| [`aws-glue-lakehouse`](./aws-glue-lakehouse) | AWS Glue, Athena, Redshift | Build a serverless lakehouse architecture on AWS |

---

## 🧰 Tech Stack

- **Languages**: Python, SQL, Shell
- **Processing**: Pandas, PySpark, Spark Streaming
- **Workflow Tools**: Apache Airflow
- **Cloud Platforms**: AWS (S3, Glue, Redshift, Athena)
- **Databases**: PostgreSQL, MongoDB, Redshift
- **Streaming**: Apache Kafka
- **Infrastructure**: Terraform, Git, Docker

---

## 📦 How to Use

Each project is self-contained with:
- `README.md`: Documentation and instructions
- `scripts/` or `notebooks/`: Codebase
- `data/`: Sample or source data
- `requirements.txt`: Dependencies (if applicable)

Clone the repo and navigate into the project folder of interest:

```bash
git clone https://github.com/kuldeepk/data-engineering-portfolio.git
cd data-engineering-portfolio/pandas-postgres-etl
