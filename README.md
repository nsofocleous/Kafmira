# Kafmira

Setup Notes for Proper Kafka Cluster Visualization
  - When setting up your Prometheus targets, please ensure the following parameters are met:
    - Desired producers are labled with job_name 'producers'
    - Desired consumers are labled with job_name 'consumers'
