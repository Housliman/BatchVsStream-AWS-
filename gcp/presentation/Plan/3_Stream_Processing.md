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

  ## Key Google Cloud Services for Stream Processing:

  - [ ] **Pub/Sub:** For ingesting and storing real-time data streams.
  - [ ] **Dataflow:** For loading, transforming, and processing streaming data.
  - [ ] **Google Cloud Functions:** Event-driven, serverless compute for processing individual events.
  - [ ] **Managed Kafka services (e.g., Confluent Cloud):** For managed Kafka workflows.
  - [ ] **Dataproc:** For running Spark Streaming or Flink on a managed cluster.

* ## Pros & Cons:

    - [ ] **Pros:** Real-time insights, immediate response to events, highly scalable.
    - [ ] **Cons:** Can be more complex to design and manage, potential for higher operational costs, requires handling out-of-order data.