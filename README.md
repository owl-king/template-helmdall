# Helmdall for single server

Note: This setup is for single server only which no HA in place. Please consider Kubernetes or Docker swarm to have more resilience on your setup

This module includes:
- Heimdall
- SSL enabled and protected by middleware authelia
- Automatically restart when it got crashed or startup
- Configs with traefik ( Basic setup with traefik can be found [Template Traefik](https://github.com/owl-king/template-traefik) )
- Run on *traefik* network

## Deployment

```bash
# Deploy traefik repo first
# Create .env from .env.example
docker-compose up -d			# Spin up containers
```
