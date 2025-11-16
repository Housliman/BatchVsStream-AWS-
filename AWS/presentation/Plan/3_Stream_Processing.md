# 3. Deep Dive: Stream Processing


  ## Characteristics:

  - [ ] Data Volume:** Small, unbounded, continuous data streams.
  - [ ] Latency:** Low latency (sub-second to seconds).
  - [ ] Throughput:** Can handle high-velocity data.
  - [ ] Execution:** Continuous, event-driven processing.

  ## Common Use Cases:

  - [ ] Real-time fraud detection in financial transactions.
  - [ ] IoT sensor data monitoring and alerting.
  - [ ] Live leaderboards for gaming applications.
  - [ ] Clickstream analysis for websites and mobile apps.

  ## Key AWS Services for Stream Processing:

  - [ ] **Amazon Kinesis:**
    - [ ] **Kinesis Data Streams:** For ingesting and storing real-time data streams.
    - [ ] **Kinesis Data Firehose:** For loading streaming data into data stores.
    - [ ] **Kinesis Data Analytics:** For processing streams with SQL or Apache Flink.

  - [ ] **AWS Lambda:** Event-driven, serverless compute for processing individual events.

  - [ ] **Amazon Managed Streaming for Apache Kafka (MSK):** Fully managed Kafka service.

  - [ ] **Amazon EMR:** For running Spark Streaming or Flink on a managed cluster.

* ## Pros & Cons:

    - [ ] **Pros:** Real-time insights, immediate response to events, highly scalable.
    - [ ] **Cons:** Can be more complex to design and manage, potential for higher operational costs, requires handling out-of-order data.
