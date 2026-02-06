# Homelab Infrastructure

## Overview
Personal homelab running on Raspberry Pi with Docker.

## Current Stack

### Services
- **Homepage** - Dashboard for all services
- **n8n** - Workflow automation platform
- **Portainer** - Docker container management

### Infrastructure
- **Platform:** Raspberry Pi
- **OS:** [укажи свою ОС, например Raspberry Pi OS]
- **Container Runtime:** Docker + Docker Compose
- **Storage:** Docker volumes

## Quick Start
```bash
# Clone repository
git clone [your-repo-url]

# Start services
cd docker-compose
docker-compose up -d
```

## Architecture
```
┌─────────────────────────────────┐
│      Raspberry Pi               │
│  ┌───────────────────────────┐  │
│  │   Docker Engine           │  │
│  │  ┌─────────┐ ┌─────────┐ │  │
│  │  │homepage │ │   n8n   │ │  │
│  │  └─────────┘ └─────────┘ │  │
│  │  ┌─────────┐              │  │
│  │  │portainer│              │  │
│  │  └─────────┘              │  │
│  └───────────────────────────┘  │
└─────────────────────────────────┘
```

## Roadmap
- [ ] Add monitoring (Prometheus + Grafana)
- [ ] Implement CI/CD pipeline
- [ ] Migrate to Kubernetes (k3s)
- [ ] Infrastructure as Code (Terraform/Ansible)

## Documentation
See [docs/](docs/) folder for detailed documentation.

---

**Status:** 🚀 Active Development
**Started:** February 2026
**Goal:** Production-ready homelab & DevOps portfolio
