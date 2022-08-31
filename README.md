# Useful Docker compose files

## PostgreSQL

```bash
docker-compose up -d postgres
docker-compose up -d pgadmin

docker-compose down
```

### Access to postgres:

    localhost:5432
    Username: postgres (as a default)
    Password: changeme (as a default)

### Access to PgAdmin:

    URL: http://localhost:5050
    Username: pgadmin4@pgadmin.org (as a default)
    Password: admin (as a default)

### Add a new server in PgAdmin:

    Host name/address postgres
    Port 5432
    Username as POSTGRES_USER, by default: postgres
    Password as POSTGRES_PASSWORD, by default changeme

