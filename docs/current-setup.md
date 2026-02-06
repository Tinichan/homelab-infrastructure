# Current Setup Documentation

## Last Updated
February 6, 2026

## Hardware
- **Device:** Raspberry Pi [модель]
- **RAM:** [сколько GB]
- **Storage:** [размер SD карты/SSD]
- **Network:** [ethernet/wifi]

## Software Stack

### Operating System
- **OS:** [например, Raspberry Pi OS 64-bit]
- **Kernel:** `uname -r`

### Docker
- **Version:** `docker --version`
- **Compose Version:** `docker-compose --version`

## Services Configuration

### Homepage
- **Port:** [какой порт]
- **Volume:** [название volume]
- **Purpose:** Dashboard для всех сервисов

### n8n
- **Port:** [какой порт]
- **Volume:** [название volume]
- **Purpose:** Workflow automation
- **Use cases:** [что автоматизируешь]

### Portainer
- **Port:** [какой порт]
- **Volume:** [название volume]
- **Purpose:** Docker GUI management

## Network Configuration
- **Network Mode:** [bridge/host]
- **Exposed Ports:** [список портов]

## Data Persistence
All data stored in Docker volumes:
```bash
docker volume ls
```

## Future Improvements
- Add reverse proxy (Traefik/Nginx)
- SSL certificates (Let's Encrypt)
- Automated backups
- Monitoring stack
