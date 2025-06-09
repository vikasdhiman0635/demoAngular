#Docker Command
docker build -t angular-docker .
docker images
docker run -p 4201:4200 angular-docker
docker ps
