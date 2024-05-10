# The Form docker compose up
## Environment variables:
1. `.env.postgres.local`
2. `.env.server.local`
3. `.env.client.local`
## Up:
1. `touch .env.postgres.local`
2. `touch .env.server.local`
3. `touch .env.client.local`
4. `docker-compose down --rmi all && docker-compose pull && docker-compose up -d`