# Professional Services
Common solutions and tools developed by Google Cloud's Professional Services team.

## Examples
The examples folder contains example solutions across a variety of Google Cloud Platform products. Use these solutions as a reference for your own or extend them to fit your particular use case.

* [BigQuery Cross Project Slot Monitoring](/examples/bigquery-cross-project-slot-monitoring) - Solution to help monitoring slot utilization across multiple projects, while breaking down allocation per project.
* [Cloud Composer Examples](/examples/cloud-composer-examples) - Examples of using Cloud Composer, GCP's managed Apache Airflow service.
* [CloudML Bee Health Detection](/examples/cloudml-bee-health-detection) - Detect if a bee is unhealthy based on an image of it and its subspecies.
* [CloudML Energy Price Forecasting](/examples/cloudml-energy-price-forecasting) - Predicting the future energy price based on historical price and weather.
* [CloudML Fraud Detection](/examples/cloudml-fraud-detection) - Fraud detection model for credit-cards transactions.
* [CloudML Sentiment Analysis](/examples/cloudml-sentiment-analysis) - Sentiment analysis for movie reviews using TensorFlow `RNNEstimator`.
* [Dataflow Elasticsearch Indexer](/examples/dataflow-elasticsearch-indexer) - An example pipeline that demonstrates the process of reading JSON documents from Cloud Pub/Sub, enhancing the document using metadata stored in Cloud Bigtable and indexing those documents into [Elasticsearch](https://www.elastic.co/).
* [Dataflow Python Examples](/examples/dataflow-python-examples) - Various ETL examples using the Dataflow Python SDK.
* [Dataflow Streaming Benchmark](/examples/dataflow-streaming-benchmark) - Utility to publish randomized fake JSON messages to a Cloud Pub/Sub topic at a configured QPS.
* [IoT Nirvana](/examples/iot-nirvana) - An end-to-end Internet of Things architecture running on Google Cloud Platform.
* [Spinnaker](/examples/spinnaker) - Example pipelines for a Canary / Production deployment process.

## Tools
The tools folder contains ready-made utilities which can simpilfy Google Cloud Platform usage.

* [CloudConnect](/tools/cloudconnect) - A package that automates the setup of dual VPN tunnels between AWS and GCP.
* [DNS Sync](/tools/dns-sync) - Sync a Cloud DNS zone with GCE resources. Instances and load balancers are added to the cloud DNS zone as they start from compute_engine_activity log events sent from a pub/sub push subscription. Can sync multiple projects to a single Cloud DNS zone.
* [GCE Quota Sync](/tools/gce-quota-sync) - A tool that fetches resource quota usage from the GCE API and synchronizes it to Stackdriver as a custom metric, where it can be used to define automated alerts.
* [GKE Billing Export](/tools/gke-billing-export) - Google Kubernetes Engine fine grained billing export.
* [LabelMaker](/tools/labelmaker) - A tool that reads key:value pairs from a json file and labels the running instance and all attached drives accordingly.
* [Site Verification Group Sync](/tools/site-verification-group-sync) - A tool to provision "verified owner" permissions (to create GCS buckets with custom dns) based on membership of a Google Group.

## Contributing
The team is currently not accepting contributions.

## License
See [LICENSE](/LICENSE)

## Disclaimer
This repository and its contents are not an official Google Product.

## Contact
Questions, issues, and comments should be directed to
[professional-services-oss@google.com](mailto:professional-services-oss@google.com).
