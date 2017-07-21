echo "http://139.59.62.228:9090" | docker secret create base-url -
docker stack deploy -c docker-compose.yml experiencedevops
