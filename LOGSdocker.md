masharodionova@MashaRodionova Docker % docker-compose down
[+] Running 2/1
⠿ Container docker-postgres-1  Removed                                                                                                                                0.2s
⠿ Network docker_default       Removed                                                                                                                                0.1s
masharodionova@MashaRodionova Docker % docker-compose up
[+] Running 2/2
⠿ Network docker_default       Created                                                                                                                                0.0s
⠿ Container docker-postgres-1  Created                                                                                                                                0.0s
Attaching to docker-postgres-1
docker-postgres-1  |
docker-postgres-1  | PostgreSQL Database directory appears to contain a database; Skipping initialization
docker-postgres-1  |
docker-postgres-1  | 2022-09-27 12:48:11.382 UTC [1] LOG:  starting PostgreSQL 12.12 on aarch64-unknown-linux-musl, compiled by gcc (Alpine 11.2.1_git20220219) 11.2.1 20220219, 64-bit
docker-postgres-1  | 2022-09-27 12:48:11.383 UTC [1] LOG:  listening on IPv4 address "0.0.0.0", port 5432
docker-postgres-1  | 2022-09-27 12:48:11.383 UTC [1] LOG:  listening on IPv6 address "::", port 5432
docker-postgres-1  | 2022-09-27 12:48:11.386 UTC [1] LOG:  listening on Unix socket "/var/run/postgresql/.s.PGSQL.5432"
docker-postgres-1  | 2022-09-27 12:48:11.413 UTC [22] LOG:  database system was shut down at 2022-09-27 12:47:45 UTC
docker-postgres-1  | 2022-09-27 12:48:11.432 UTC [1] LOG:  database system is ready to accept connections

