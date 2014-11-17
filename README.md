docker-sonar
============

Docker container with Sonar and embedded MySQL


### How to run

docker run -d -v /var/lib/mysql:/var/lib/mysql -p 9000:9000 --name "sonar" lpicanco/sonar
