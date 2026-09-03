# Deployment Process

## Standard Flow

1. Application source is prepared.
2. Docker image is built.
3. The image is stored in Artifact Registry.
4. A Cloud Run revision is deployed.
5. Application health and logs are checked.
6. Traffic is validated through the load balancer.
7. Issues are investigated through logs and infrastructure checks.

## Post-Deployment Validation

- Cloud Run revision status
- Container startup
- Application logs
- Database connectivity
- Load balancer reachability
- WAF behavior
- Application response

## Rollback

When a deployment introduces an application or runtime issue, the known-good Cloud Run revision can be used as the recovery point where supported by the deployment configuration.
