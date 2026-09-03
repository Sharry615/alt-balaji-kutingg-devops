# Cloud SQL / PostgreSQL

Cloud SQL provided the managed PostgreSQL database layer for the application platform.

## DevOps Work

- Supported PostgreSQL connectivity from application services
- Investigated application-to-database connectivity failures
- Reviewed database-related application errors and logs
- Troubleshot network and connection configuration
- Supported database availability troubleshooting

## Connectivity Flow

```text
Cloud Run
    |
    v
VPC / Network Connectivity
    |
    v
Cloud SQL
    |
    v
PostgreSQL
```

## Troubleshooting Areas

- Connectivity
- Authentication/configuration
- Network path
- Connection failures
- Application logs
- Database availability
