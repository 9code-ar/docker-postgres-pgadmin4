# docker-postgres-pgadmin4

This is a docker-compose.yml project designed to simplify spinning out PostgreSQL server and client (pgadmin4)

## Quick Start

```
git clone https://github.com/9code-ar/docker-postgres-pgadmin4
cd https://github.com/9code-ar/docker-postgres-pgadmin4
docker-compose up -d
```

Then access via browser `http://localhost:5480` 
Default user is `admin@admin.com` and both user and server password are `password`

## Customization

You could create a file named `docker-compose.override.yml` to set your own super secret passwords