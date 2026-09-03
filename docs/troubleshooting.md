# Troubleshooting

## Cloud Run

Check:

- Revision status
- Container startup errors
- Application logs
- Runtime exceptions
- Environment/configuration issues

## Database Connectivity

Check:

- Application logs
- Network connectivity
- VPC connectivity
- Database availability
- Connection configuration

## Load Balancer

Check:

- Frontend reachability
- Backend/service health
- Routing
- SSL/TLS
- DNS

## Cloud Armor / WAF

Check:

- Request behavior
- Security rules
- Blocked requests
- Application availability
- Logs and traffic patterns

## General Approach

```text
Symptom
   |
   v
Application Logs
   |
   v
Cloud Run / Service Health
   |
   v
Network / Database / LB Checks
   |
   v
Root Cause
   |
   v
Fix + Validation
```
