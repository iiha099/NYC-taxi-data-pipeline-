NYC Taxi End-to-End Data Engineering Pipeline 🚕
An end-to-end data engineering pipeline built using PySpark, Apache Airflow, Google Cloud Storage, and Google Cloud Dataproc.
The pipeline ingests NYC Yellow Taxi trip data, validates and cleans the data, creates analytics and machine learning datasets, runs distributed Spark jobs on Google Cloud Dataproc, and orchestrates the complete workflow using Apache Airflow.
All PySpark transformation tests passed successfully (15/15).

🏗️ Architecture
NYC Yellow Taxi Data 
        ↓ 
Data Ingestion 
		↓
Schema Validation 
		↓
Google Cloud Storage - Raw Layer 
		↓ 
PySpark Cleaning & Transformation
		↓ 
Google Cloud Storage - Staging Layer 
		↓ 
Data Processing
	↙       ↘
Analytics      ML Dataset
					↓ 
			Model Training 
					↓
			Model Storage
Apache Airflow orchestrates the complete pipeline. Spark workloads are executed on Google Cloud Dataproc.

✅ Project Results
-Built and executed the complete end-to-end data pipeline
-Processed NYC Yellow Taxi Parquet data using PySpark
-Implemented Raw, Staging, and Processed data layers
-Submitted Spark jobs to Google Cloud Dataproc
-Created datasets for analytics and machine learning workloads
-Orchestrated the pipeline using Apache Airflow
-Implemented automated PySpark tests
-15/15 tests passed successfully
