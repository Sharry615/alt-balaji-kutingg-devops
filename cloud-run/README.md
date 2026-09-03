# Cloud Run

Cloud Run is the application execution layer for the platform's containerized services.

## DevOps Work

- Managed Cloud Run services and revisions
- Deployed container images
- Validated revision health
- Reviewed application logs
- Troubleshot container startup and runtime issues
- Investigated application-to-database connectivity
- Supported rollback to known-good revisions

## Deployment Flow

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
Load Balancer
```

## Operational Checks

- Revision status
- Container startup
- Application logs
- Runtime errors
- Database connectivity
- Service availability
