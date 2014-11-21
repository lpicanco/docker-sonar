docker-sonar
============

Docker container with Sonar and embedded MySQL


### How to run

docker run -d -v /var/lib/mysql:/var/lib/mysql -v /opt/sonar/extensions/plugins:/opt/sonar/extensions/plugins -p 9000:9000 --name "sonar" lpicanco/sonar
