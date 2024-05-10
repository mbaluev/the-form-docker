# The Form docker compose up
## Environment variables:
1. `.env.postgres`
2. `.env.server`
3. `.env.client`
## Up:
`docker-compose down --rmi all && docker-compose pull && docker-compose up -d`