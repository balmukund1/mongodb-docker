# mongodb-docker
MongoDB 3.2 docker

Install docker and excute following commands.

docker build -t mongodb .

docker run -p 27017:27017 --name mongodb -d mongodb

docker exec -it mongodb bash

docker exec -it mongodb mongo
