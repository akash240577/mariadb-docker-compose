# mariadb-docker-compose
Docker Compose yaml for mariadb image

# load initial db
docker exec -i mariadb-container mysql -ur5user -p GWN_R5 < /opt/tmp/GWN_R5.sql
