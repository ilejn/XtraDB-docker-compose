XtraDB in docker compose
========================
Based on official guide  Running Percona XtraDB Cluster in a Docker Container
https://www.percona.com/doc/percona-xtradb-cluster/LATEST/install/docker.html

Certificates are included

Just
1. docker-compose up
2. docker-compose exec xtradb-master mysql -uroot
3. docker-compose exec xtradb-slave1 mysql -uroot
