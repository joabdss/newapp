# Meu Projeto Docker

Este é um projeto web simples com HTML e CSS, servido via Nginx dentro de um container Docker.

## Como rodar o projeto

1. Clone este repositório:
```sh
git clone https://github.com/joabdss/newapp.git
cd newapp

Build and run
Build image:

docker build -t joabdss/newapp:1.0.0 .

Run a container:

docker run -d -p 80:8080 --rm --name newapp joabdss/newapp:1.0.0


Access http://DOCKER_HOST_IP in browser.
Push to Docker Hub:

docker login -u your_dockerhub_username
docker push joabdss/newapp:1.0.0
```