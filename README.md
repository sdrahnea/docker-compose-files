# docker-compose-files
A repository which contains scripts to start services via docker

# commands:
- sudo docker-compose down
```
Removing postgres ... done
```
- sudo docker-compose up --force-recreate
```
Recreating postgres ... 
Recreating postgres ... done
Attaching to postgres
postgres    | 
postgres    | PostgreSQL Database directory appears to contain a database; Skipping initialization
postgres    | 
postgres    | 2019-12-27 08:54:29.342 UTC [1] LOG:  starting PostgreSQL 12.1 (Debian 12.1-1.pgdg100+1) on x86_64-pc-linux-gnu, compiled by gcc (Debian 8.3.0-6) 8.3.0, 64-bit
postgres    | 2019-12-27 08:54:29.342 UTC [1] LOG:  listening on IPv4 address "0.0.0.0", port 5432
postgres    | 2019-12-27 08:54:29.342 UTC [1] LOG:  listening on IPv6 address "::", port 5432
postgres    | 2019-12-27 08:54:29.344 UTC [1] LOG:  listening on Unix socket "/var/run/postgresql/.s.PGSQL.5432"
postgres    | 2019-12-27 08:54:29.354 UTC [25] LOG:  database system was shut down at 2019-12-27 08:47:36 UTC
postgres    | 2019-12-27 08:54:29.358 UTC [1] LOG:  database system is ready to accept connections
```
