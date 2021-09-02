# DockerCompose-redmine-mysql
docker compose standalone 


I put docker project in 
/srv/docker/XXXXXX
XXXX is name of my project

so this project should go to /srv/docker/redmine

he run with 
redmine:4.2-passenger
mysql:5.7

on port 80


an adminer is her for maintenance on port 3001


you can create init.d boot with symlink
ln -s /srv/docker/redmine/serviceDockerComposeRedmine.sh /etc/init.d/serviceDockerComposeRedmine.sh