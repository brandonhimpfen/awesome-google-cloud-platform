# Awesome Google Cloud Platform (GCP) [![Awesome Lists](https://srv-cdn.himpfen.io/badges/awesome-lists/awesomelists-flat.svg)](https://github.com/awesomelistsio/awesome)

[![DOI](https://zenodo.org/badge/1106659624.svg)](https://doi.org/10.5281/zenodo.19673362)  
[![GitHub Sponsor](https://srv-cdn.himpfen.io/badges/github/github-flat.svg)](https://github.com/sponsors/brandonhimpfen) &nbsp; 
[![Buy Me a Coffee](https://srv-cdn.himpfen.io/badges/buymeacoffee/buymeacoffee-flat.svg)](https://buymeacoffee.com/brandonhimpfen) &nbsp; 
[![Ko-Fi](https://srv-cdn.himpfen.io/badges/kofi/kofi-flat.svg)](https://ko-fi.com/brandonhimpfen) &nbsp; 
[![PayPal](https://srv-cdn.himpfen.io/badges/paypal/paypal-flat.svg)](https://paypal.me/brandonhimpfen)

📌 This repository is archived with Zenodo and can be cited using the DOI above.

> A curated list of tools, SDKs, libraries, client utilities, learning resources, templates, and ecosystem components for **Google Cloud Platform (GCP)** — including Compute, Networking, Storage, Big Data, AI/ML, IAM, Serverless, and DevOps.

_Support ongoing maintenance and curation via [GitHub Sponsors](https://github.com/sponsors/brandonhimpfen)._

## Contents

- [Official Resources](#official-resources)
- [Compute](#compute)
- [Serverless](#serverless)
- [Storage](#storage)
- [Databases](#databases)
- [Networking & Security](#networking--security)
- [Big Data & Analytics](#big-data--analytics)
- [AI & Machine Learning](#ai--machine-learning)
- [DevOps & CI/CD](#devops--cicd)
- [SDKs & Libraries](#sdks--libraries)
- [CLI Tools](#cli-tools)
- [Monitoring & Observability](#monitoring--observability)
- [Terraform & IaC](#terraform--iac)
- [Learning Resources](#learning-resources)
- [Related Awesome Lists](#related-awesome-lists)

## Official Resources

- [Google Cloud Documentation](https://cloud.google.com/docs)
- [Google Cloud Console](https://console.cloud.google.com/)
- [Google Cloud GitHub](https://github.com/googleapis)
- [Google Cloud Samples](https://cloud.google.com/samples)
- [Google Cloud Architecture Center](https://cloud.google.com/architecture)
- [Google Cloud Status Dashboard](https://status.cloud.google.com/)

## Compute

- [Compute Engine](https://cloud.google.com/compute) – Virtual machines running on GCP.
- [GKE – Google Kubernetes Engine](https://cloud.google.com/kubernetes-engine) – Managed Kubernetes service.
- [Cloud Run](https://cloud.google.com/run) – Serverless container execution.
- [Migrate to Containers](https://cloud.google.com/migrate/containers) – Containerize and modernize workloads.
- [Batch API](https://cloud.google.com/batch) – Batch job execution at scale.

## Serverless

- [Cloud Functions](https://cloud.google.com/functions) – Event-driven serverless functions.
- [Cloud Run Jobs](https://cloud.google.com/run/docs/execute/jobs) – Serverless batch execution.
- [Workflows](https://cloud.google.com/workflows) – Orchestration across GCP services.

## Storage

- [Cloud Storage](https://cloud.google.com/storage) – Object storage.
- [Filestore](https://cloud.google.com/filestore) – High-performance file storage.
- [Local SSD + Persistent Disk](https://cloud.google.com/compute/docs/disks) – Storage options for Compute Engine.

## Databases

- [Cloud SQL](https://cloud.google.com/sql) – Managed MySQL, PostgreSQL, SQL Server.
- [Cloud Spanner](https://cloud.google.com/spanner) – Horizontally scalable relational database.
- [Firestore](https://cloud.google.com/firestore) – NoSQL serverless document database.
- [Bigtable](https://cloud.google.com/bigtable) – High-throughput, low-latency NoSQL wide-column store.
- [MemoryStore](https://cloud.google.com/memorystore) – Managed Redis and Memcached.

## Networking & Security

- [VPC](https://cloud.google.com/vpc) – Virtual network management.
- [Cloud Armor](https://cloud.google.com/armor) – DDoS and WAF protection.
- [Cloud Load Balancing](https://cloud.google.com/load-balancing) – Global L7/L4 load balancing.
- [BeyondCorp / Zero Trust](https://cloud.google.com/beyondcorp) – Zero-trust access model.
- [IAM](https://cloud.google.com/iam) – Identity and access management.

## Big Data & Analytics

- [BigQuery](https://cloud.google.com/bigquery) – Serverless data warehouse.
- [Dataflow](https://cloud.google.com/dataflow) – Streaming + batch processing (Apache Beam).
- [Pub/Sub](https://cloud.google.com/pubsub) – Messaging middleware.
- [Dataproc](https://cloud.google.com/dataproc) – Managed Spark/Hadoop clusters.
- [Looker](https://cloud.google.com/looker) – Modern BI and analytics platform.

## AI & Machine Learning

- [Vertex AI](https://cloud.google.com/vertex-ai) – Unified ML platform.
- [Vertex AI Search](https://cloud.google.com/generative-ai) – Enterprise search and RAG.
- [Vertex AI Agent Builder](https://cloud.google.com/agent-builder) – Build AI agents and chat interfaces.
- [AutoML](https://cloud.google.com/automl) – Train ML models without deep coding.
- [TPU](https://cloud.google.com/tpu) – Specialized ML acceleration hardware.

## DevOps & CI/CD

- [Cloud Build](https://cloud.google.com/build) – Build, test, and deploy automation.
- [Cloud Deploy](https://cloud.google.com/deploy) – CI/CD for Kubernetes.
- [Artifact Registry](https://cloud.google.com/artifact-registry) – Container and artifact storage.
- [Skaffold](https://github.com/GoogleContainerTools/skaffold) – Kubernetes workflow automation.

## SDKs & Libraries

- [Google Cloud SDK](https://cloud.google.com/sdk) – Core SDK.
- [google-cloud-python](https://github.com/googleapis/google-cloud-python) – Python client libraries.
- [google-cloud-go](https://github.com/googleapis/google-cloud-go) – Go client libraries.
- [google-cloud-node](https://github.com/googleapis/google-cloud-node) – Node.js client libraries.
- [google-cloud-java](https://github.com/googleapis/java-cloud-bom) – Java client libraries.
- [google-cloud-rust](https://github.com/googleapis) – Community Rust client projects.

## CLI Tools

- [gcloud CLI](https://cloud.google.com/sdk/gcloud) – Manage GCP services from the command line.
- [gsutil](https://cloud.google.com/storage/docs/gsutil) – Cloud Storage operations.
- [bq CLI](https://cloud.google.com/bigquery/docs/bq-command-line-tool) – BigQuery command-line tool.
- [kubectl](https://kubernetes.io/docs/) – Kubernetes CLI for GKE.

## Monitoring & Observability

- [Cloud Monitoring](https://cloud.google.com/monitoring) – Metrics, dashboards, SLOs.
- [Cloud Logging](https://cloud.google.com/logging) – Centralized logs with query and routing.
- [Error Reporting](https://cloud.google.com/error-reporting) – Automatic error aggregation.
- [Cloud Trace](https://cloud.google.com/trace) – Distributed tracing.
- [Cloud Profiler](https://cloud.google.com/profiler) – Performance analysis.

## Terraform & IaC

- [Google Cloud Terraform Provider](https://github.com/hashicorp/terraform-provider-google) – Terraform provider for GCP.
- [Terraform GCP Modules](https://github.com/terraform-google-modules) – Production-ready configurations.
- [Pulumi + GCP](https://www.pulumi.com/docs/) – Infrastructure-as-code in TypeScript/Python/Go.

## Learning Resources

- [Google Cloud Skills Boost](https://www.cloudskillsboost.google/) – Labs, quests, and learning paths.
- [Google Cloud YouTube Channel](https://www.youtube.com/user/googlecloudplatform) – Tutorials and announcements.
- [Google Cloud Blog](https://cloud.google.com/blog/) – Official updates and engineering insights.
- [Awesome Google Cloud Learning Paths](https://cloud.google.com/training) – Certification and learning content.
- [Architecting on Google Cloud](https://cloud.google.com/training/architect) – Certification prep.

## Related Awesome Lists

- [Awesome Web Development](https://github.com/awesomelistsio/awesome-web-development)
- [Awesome Cloud Computing](https://github.com/awesomelistsio/awesome-cloud-computing)
- [Awesome DevOps](https://github.com/awesomelistsio/awesome-devops)
- [Awesome AI Infrastructure](https://github.com/awesomelistsio/awesome-ai-infrastructure)

## Contribute

Contributions are welcome. Please ensure your submission fully follows the requirements outlined in [`CONTRIBUTING.md`](CONTRIBUTING.md), including formatting, scope alignment, and category placement.

Pull requests that do not adhere to the contribution guidelines may be closed.

## License

[![CC0](https://mirrors.creativecommons.org/presskit/buttons/88x31/svg/by-sa.svg)](http://creativecommons.org/licenses/by-sa/4.0/)
