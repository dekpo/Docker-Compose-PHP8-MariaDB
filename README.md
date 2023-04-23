# Just run docker-compose up -d
docker-compose up -d

This simple command will load 3 containers
- mariadb (service named db) using 3306 default port and creating local db-data folder for data persistence
- adminer (service named adminer) accessible at localhost:8080
- php (service named php) based on a custom image using http:80 and https:443 default ports creating local htdocs folder for php coding

Enjoy ;)
