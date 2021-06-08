# Jibber-Jabber-Deploy

## Update Service

`docker-compose -f docker-compose.prod.yml up -d --no-deps <service>`

## .env File format example

`POSTGRES_USER=admin POSTGRES_PASSWORD=admin PGADMIN_DEFAULT_EMAIL=admin@admin.com PGADMIN_DEFAULT_PASSWORD=admin POSTGRES_DB=dev POSTGRES_DB_HOST=pg-db`
