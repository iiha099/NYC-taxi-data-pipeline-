NYC Taxi End-to-End Data Engineering Pipeline 🚕
An end-to-end data engineering pipeline built using PySpark, Apache Airflow, Google Cloud Storage, and Google Cloud Dataproc.
The pipeline ingests NYC Yellow Taxi trip data, validates and cleans the data, creates analytics and machine learning datasets, runs distributed Spark jobs on Google Cloud Dataproc, and orchestrates the complete workflow using Apache Airflow.
All PySpark transformation tests passed successfully (15/15).

🏗️ Architecture
NYC Yellow Taxi Data
        |
        v
Data Ingestion
        |
        v
Schema Validation
        |
        v
GCS - Raw Layer
        |
        v
PySpark Cleaning & Transformation
        |
        v
GCS - Staging Layer
        |
        v
Data Processing
     /       \
    v         v
Analytics   ML Dataset
              |
              v
        Model Training
              |
              v
        Model Storage

🛠️ Technologies
- Python
- PySpark
-  Apache Spark
- Apache Airflow
- Google Cloud Storage
- Google Cloud Dataproc
- Docker
- Pytest
- Git

  
✅ Results
-Built and executed the complete end-to-end data pipeline
-Processed NYC Yellow Taxi Parquet data using PySpark
-Implemented Raw, Staging, and Processed data layers
-Submitted Spark jobs to Google Cloud Dataproc
-Created datasets for analytics and machine learning workloads
-Orchestrated the pipeline using Apache Airflow
-Implemented automated PySpark tests
-15/15 tests passed successfully

