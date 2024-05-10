# The Form docker compose up
## Environment variables:
1. `.env.postgres.local`
2. `.env.client.local`
3. `.env.server.local`
## Up:
`docker-compose down --rmi all && docker-compose pull && docker-compose up -d`