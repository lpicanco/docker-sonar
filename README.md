docker-sonar
============

Docker container with Sonar and embedded MySQL


### How to run

# Give your container a name to recognize it by
CONTAINER_NAME="sonar"

docker run -d -v /var/lib/mysql:/var/lib/mysql -p 9000:9000 --name "sonar" lpicanco/sonar
