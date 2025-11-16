# 2. Deep Dive: Batch Processing


## Characteristics:

- [ ] **Data Volume:** Large, bounded datasets.
- [ ] **Latency:** High latency (minutes to hours).
- [ ] **Throughput:** High throughput is a primary goal.
- [ ] **Execution:** Scheduled, periodic jobs.

## Common Use Cases:

- [ ] End-of-day reporting and analytics.
- [ ] Payroll and billing systems.
- [ ] Large-scale ETL (Extract, Transform, Load) jobs.
- [ ] Genomic sequencing.

## Key AWS Services for Batch Processing:

- [ ] **Amazon S3:** Data lake storage for raw and processed data.
- [ ] **AWS Glue:** Serverless ETL service for data preparation and loading.
- [ ] **Amazon EMR:** Managed big data platform (Spark, Hadoop, Hive).
- [ ] **AWS Batch:** Fully managed batch computing for scheduling and executing jobs.
- [ ] **Amazon Redshift:** Data warehousing for large-scale analytics.

## Pros & Cons:

- [ ] **Pros:** Cost-effective for large datasets, high throughput, simple architecture.
- [ ] **Cons:** High latency, insights are not real-time, can be complex to manage for ad-hoc queries.
