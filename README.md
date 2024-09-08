# Version de sotware:
# - Mattermost-team-edition:8.0
# - Postgresql 15.0

# Ejecutar los siguientes pasos:
$ git clone https://github.com/Braggian/docker-mattermost/

$ cd docker-mattermost

$ mkdir -p mattermost && cd mattermost

$ mkdir -p mattermost/{config,data,logs,plugins,client/plugins,bleve-indexes} 

$ mkdir -p postgresql/data

$ chmod -R 777 mattermost/config

$ docker-compose up -d

# Ingresamos a la aplicacion web: 
Ver en "localhost:8065" ó "Ip:puerto"

