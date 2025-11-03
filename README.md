## Jenkins Credentials

URL: http://localhost:8080

Usename: admin

Password: admin123

## Docker Commands

DOCKER IMAGES COMMANDS

docker images
docker pull <image-name>
docker rmi <image-id>
docker build 


DOCKER CONT COMMANDS

docker ps -a (list all running or not running cont)
docker ps (list only running cont)
docker run <image-name>
	docker run -it ubuntu /bin/bash
	docker run -d -p 8005:80 nginx
	docker exec -it <cont-id> /bin/bash

docker stop <cont-d/name>
docker start <cont-id/name>
docker rm <cont-id>
docker rm -f $(docker ps -aq)
