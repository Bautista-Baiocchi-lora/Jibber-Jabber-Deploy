# Jibber-Jabber-Deploy

---

## Dev

### Create

`docker-compose -f docker-compose.dev.yml up --no-start`

### Start

`docker-compose -f docker-compose.dev.yml start`

### Stop

`docker-compose -f docker-compose.dev.yml stop`

### Destroy

`docker-compose -f docker-compose.dev.yml down`

---

## Production

### Create

`docker-compose -f docker-compose.prod.yml up --no-start`

### Start

`docker-compose -f docker-compose.prod.yml start`

### Stop

`docker-compose -f docker-compose.prod.yml stop`

### Destroy

`docker-compose -f docker-compose.prod.yml down`

---

## Update a specific service

`docker-compose -f docker-compose.<domain>.yml up -d --no-deps <service>`

## .env File format example

`POSTGRES_USER=admin POSTGRES_PASSWORD=admin PGADMIN_DEFAULT_EMAIL=admin@admin.com PGADMIN_DEFAULT_PASSWORD=admin POSTGRES_DB=dev POSTGRES_DB_HOST=pg-db`
