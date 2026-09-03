# Architecture

## Platform Flow

```text
Internet
   |
   v
Load Balancer
   |
   v
Cloud Armor / WAF
   |
   v
Cloud Run Services
   |              |
   v              v
Cloud SQL      Cloud Storage
   |
   v
PostgreSQL
```

## Container Deployment Flow

```text
Source Code
    |
    v
Docker Build
    |
    v
Artifact Registry
    |
    v
Cloud Run Revision
    |
    v
Application Traffic
```

## Infrastructure Components

| Component | Purpose |
|---|---|
| Cloud Run | Application execution for containerized services |
| Artifact Registry | Container image storage |
| Cloud SQL / PostgreSQL | Managed relational database |
| Load Balancer | Application traffic distribution and ingress |
| Cloud Armor / WAF | Edge security and traffic protection |
| Cloud Storage | Object/file storage |
| Cloud Monitoring & Logging | Operational visibility and troubleshooting |
