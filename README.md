# lightsail-compose

Add this to the lightsail launchscript when creating a new lightsail OS Ubuntu 16.04 instance:

`curl -o lightsail-compose.sh https://raw.githubusercontent.com/Davincium/lightsail-compose/master/lightsail-compose.sh ; chmod +x ./lightsail-compose.sh ; ./lightsail-compose.sh ; docker login -u [docker_username] -p [docker_password] ; docker-compose -f /srv/docker/docker-compose.yml up -d` 
