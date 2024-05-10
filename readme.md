# The Form docker compose up
## Environment variables
1. `.env.postgres`
2. `.env.server`
3. `.env.client`
## Up
### One command
`docker-compose down --rmi all && docker-compose pull && docker-compose up -d`
### Separate commands
1. `docker system prune -a` - clean up
1. `docker-compose down --rmi all` - stop all containers
2. `docker-compose pull` - pull all images
3. `docker-compose up -d` - up containers
