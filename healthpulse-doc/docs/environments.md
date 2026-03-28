# Environment Matrix

| Environment | Purpose | URL | Infrastructure | Notes |
|------------|--------|-----|---------------|------|
| *Development* | Local testing and development | http://localhost:8084 | Docker (local) | Used for live reload |
| *QA/UAT* | Testing before production | TBD | AWS ECS/EKS | Integration testing |
| *Production* | Live application | TBD | AWS ECS/EKS + ALB | Public access |

---

## Environment Details

### Development
- Runs locally using Docker
- Uses MkDocs live reload
- Fast iteration

### QA/UAT
- Used for testing features before production
- Includes testing pipelines and validation

### Production
- Hosted on AWS
- Uses load balancing and monitoring
- High availability and scalability

---