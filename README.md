# Northwind database for Postgres
Northwind


1. Run docker-compose
```
# docker compose up -d
```

2. Run psql client in container
```
# docker compose exec db psql -U admin -d northwind
psql (16.1 (Debian 16.1-1.pgdg120+1))
Type "help" for help.

northwind=#
```

3. Run psql client from bash in container
```
# docker compose exec db bash
root@c4adb8b1027c:/# psql -U admin -d northwind
psql (16.1 (Debian 16.1-1.pgdg120+1))
Type "help" for help.

northwind=#
```
