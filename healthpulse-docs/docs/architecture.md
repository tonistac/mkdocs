# Architecture Decisions

## ADR-001: CI/CD Platform Selection

### Decision
We chose *GitLab CI/CD* as our pipeline platform.

### Justification
- Built-in CI/CD integration with Git repository
- Supports pipelines, merge requests, and automation
- Easy to configure for student teams
- No need for separate Jenkins server setup

### Alternatives Considered
- Jenkins → More complex setup and maintenance
- Azure DevOps → Less aligned with our current workflow

---

## ADR-002: Cloud Platform Selection

### Decision
We chose *Amazon Web Services (AWS)* as our cloud provider.

### Justification
- Industry-standard cloud platform
- Supports ECS, EKS, ALB, VPC, and Route 53
- Scalable and production-ready infrastructure
- Strong integration with DevOps tools

---

## ADR-003: Containerization Strategy

### Decision
Use *Docker with multi-stage builds*

### Justification
- Ensures consistent environments across development and production
- Reduces "works on my machine" issues
- Enables CI/CD automation
- Optimizes image size using multi-stage builds

---

## ADR-004: Orchestration Strategy

### Decision
Use *Kubernetes (EKS)* for container orchestration

### Justification
- Industry-standard orchestration platform
- Supports scaling, load balancing, and resilience
- Aligns with modern DevOps practices

---