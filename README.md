unsafe-postgres
===============

```bash
# build image
docker build -t unsafe_postgres .

# run container
docker run --name <NAME> -e POSTGRES_USER=$USER -p 5432:5432 unsafe_postgres
```
