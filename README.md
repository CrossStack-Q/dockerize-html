# Dockerize APP

## sudo vim Dockerfile

systemctl status docker

sudo docker build . -t portfolio:v1.0    

sudo docker run -p 8000:80 portfolio:v1.0 

docker login

sudo docker image tag portfolio:v1.0 crayonhero/portfolio:v1.0

docker images       

sudo docker push crayonhero/portfolio:v1.0


# exit
