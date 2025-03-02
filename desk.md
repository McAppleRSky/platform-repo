```bash
docker run --name platform-repo -p5432:5432 \-e PSQL_DB=platform \
-e PSQL_PASSWORD=$(cat .username)\
-e PSQL_USERNAME=$(cat .password)
```
