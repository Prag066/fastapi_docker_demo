# fastapi_docker_demo


# build docker image
sudo docker build -t api .

# run docker container
sudo docker run -d --name mycontainer -p 80:80 api

# run kill container
sudo docker kill mycontainer

# run stop docker container
sudo docker stop mycontainer

# run remove docker stopped container
sudo docker container prune


# run remove docker images
sudo docker image prune -a
