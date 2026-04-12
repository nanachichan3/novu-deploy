# Novu Self-Hosted Deployment

Self-hosted Novu notification infrastructure for the AI Startup Factory.

## Services

| Service | Image | Purpose |
|---------|-------|---------|
| mongodb | mongo:8.0.17 | Primary database |
| redis | redis:alpine | Caching & queues |
| api | ghcr.io/novuhq/novu/api:3.14.0 | REST API |
| worker | ghcr.io/novuhq/novu/worker:3.14.0 | Background jobs |
| ws | ghcr.io/novuhq/novu/ws:3.14.0 | WebSocket server |
| dashboard | ghcr.io/novuhq/novu/dashboard:3.14.0 | Admin UI (port 4000) |

## Access

- **Dashboard:** https://novu.qed.quest
- **API:** Internal only (port 3000)

## Deployment

Deployed on Coolify — `nanachichan3/novu-deploy` repo, `deploy/` directory.

## Docs

https://novu.co/docs
