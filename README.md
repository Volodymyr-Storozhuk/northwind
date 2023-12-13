# Database Northwind
Northwind

Run psql in container
```
# docker compose exec db psql -U admin -d northwind
psql (16.1 (Debian 16.1-1.pgdg120+1))
Type "help" for help.

northwind=#
```

or run psql from bash in container
```
# docker compose exec db bash
root@c4adb8b1027c:/# psql -U admin -d northwind
psql (16.1 (Debian 16.1-1.pgdg120+1))
Type "help" for help.

northwind=#
```
