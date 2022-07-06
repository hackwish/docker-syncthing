Docker Syncthing client config
---------------------------------

Using Docker package to config Syncthing client

## Requirements
- Docker
- Docker Compose

## How-to:
### - Clone the specific branch
``git clone https://github.com/hackwish/docker-syncthing.git syncthing``

### - Enter into "syncthing" folder
``cd syncthing``

## Start

- Edit "docker-compose.override" to add new/own sources
``docker-compose --compatibility up -d``

Based on <https://github.com/linuxserver/docker-syncthing/pkgs/container/syncthing>
