# POSTGRES

To start postgres: 
```bash
postgres-start
# alias for 
pg_ctl -D /usr/local/var/postgres -l /usr/local/var/postgres/server.log start
```
To stop postgres: 
```bash
postgres-stop
# alias for 
pg_ctl -D /usr/local/var/postgres stop -s -m fast
```
