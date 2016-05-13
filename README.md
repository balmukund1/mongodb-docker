# mongodb-docker
MongoDB 3.2 docker

Install docker and excute following commands.

docker build -t mongo .

docker run -p 27017:27017 --name mongodb -d mongo

docker exec -it mongodb bash

docker exec -it mongodb mongo
