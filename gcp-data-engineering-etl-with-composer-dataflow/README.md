# <img width="40" alt="image" src="https://github.com/janaom/gcp-data-engineering-etl-with-composer-dataflow/assets/83917694/60f8f158-3bdc-4b3d-94ae-27a12441e2a3"> GCP Data Engineering Project: ETL Pipeline for Online Food Delivery Industry

This project focuses on developing a **robust ETL (Extract, Transform, Load) pipeline** for the online food delivery industry. The pipeline handles **batch transactional data** and uses several Google Cloud Platform (GCP) services.

## Technologies Used
- **Google Cloud Storage (GCS)**: Stores and manages transactional data
- **Composer (Airflow)**: Orchestrates Dataflow jobs
- **Dataflow (Apache Beam)**: Processes, transforms, and loads data into BigQuery
- **BigQuery**: Serverless data warehouse
-**Looker Studio**: Generates daily reports

These components work together to efficiently **process, store, and visualize transactional data**.

![GCP-Diagram](https://github.com/janaom/gcp-data-engineering-etl-with-composer-dataflow/assets/83917694/f3a7ff86-92b3-46db-a156-e5ebbefc3bb9)

---

## GCS
Upload the CSV file to your **GCS bucket**. The dataset contains:
- Customer ID, date, time, order ID
- Items ordered, transaction amount, payment mode
- Restaurant name, order status, ratings, feedback

This data reflects real-world scenarios like **late delivery, stale food, and complicated orders**, providing valuable insights.

![GCS Sample](https://github.com/janaom/gcp-data-engineering-project-food-orders-etl/assets/83917694/285dcfd6-f212-418b-b5bc-e56beb35fa52)

---

