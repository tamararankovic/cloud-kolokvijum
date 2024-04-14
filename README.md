# Environment varijable

- DB_HOST=movies-postgres2.cnu6a6yckjrr.eu-central-1.rds.amazonaws.com
- DB_PORT=5432
- DB_NAME=movies_db
- DB_USER=postgres
- DB_PASS=postgres

# API

Aplikacija sluša na portu **8080**

- **GET /movies** - Dobavljanje svih filmova
- **POST /movies** - Dodavanje novog filma

# Komanda za testiranje

```
docker run -p 8080:8080 -e DB_HOST=movies-postgres2.cnu6a6yckjrr.eu-central-1.rds.amazonaws.com -e DB_PORT=5432 -e DB_NAME=movies_db -e DB_USER=postgres -e DB_PASS=postgres tamarar/cloud-app
```