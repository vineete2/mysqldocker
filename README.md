To run the Mysql server:
docker-compose up

To connect to database:
docker-compose exec mysql-dev mysql -uroot -p12345 dbpedia_metrics

To check databases:
show databases;
