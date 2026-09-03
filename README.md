# ALT Balaji / Kutingg.com — DevOps & GCP Infrastructure

## Project Overview

This repository documents DevOps and Google Cloud Platform infrastructure work for the ALT Balaji platform, currently associated with Kutingg.com.

The documentation focuses on the infrastructure, deployment, operations, troubleshooting, and security responsibilities handled as part of the platform.

## Infrastructure

- Google Cloud Run
- Cloud SQL / PostgreSQL
- Google Cloud Load Balancing
- Google Cloud Storage
- Google Cloud Armor / WAF
- Docker
- Artifact Registry
- Cloud Monitoring and Logging

## High-Level Architecture

```text
Internet Users
      |
      v
Google Cloud Load Balancer
      |
      v
Cloud Armor / WAF
      |
      v
Cloud Run Services
      |------|
      v      v
Cloud SQL   Cloud Storage
      ^
      |
Artifact Registry
      ^
      |
Docker Images
```

## DevOps Scope

- Containerized application deployment
- Cloud Run service and revision operations
- Docker image management
- Artifact Registry usage
- Cloud SQL / PostgreSQL connectivity troubleshooting
- Load balancer and application traffic flow
- Cloud Storage operations
- Cloud Armor / WAF configuration and troubleshooting
- Monitoring and application log investigation
- Production issue troubleshooting

## Repository Structure

```text
architecture/
cloud-run/
cloud-sql/
load-balancer/
cloud-storage/
cloud-armor-waf/
cicd/
docs/
```

## Security Note

This repository intentionally excludes credentials, secrets, private IP addresses, internal hostnames, production configuration values, tokens, and other confidential infrastructure details.
