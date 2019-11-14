# MediaBox

![Image of MediaBox](MediaBox.png)


# About
  MediaBox is a Docker-Compose file consiting of all the relevant components to setup your own Media Server.

## Includes
* NGINX - Reverse Proxy for all services
* Portainer - Container management UI
* Plex - Media Server for TV, Moves & Music
* Sonarr - TV Series management tool.
* Radarr - Moves management tool.
* Deluge - Torrent client with OpenVPN.
* Ombi - Media request client.
* Tautulli - Plex Server monitoring.
* Cardigann - Torrent Indexer
* TV Headend - Linux TV Streamer.

## Requirements
* Docker
* Docker-Compose

## Instructions 
* Clone Repo to ~/docker
* Modify .env file
* Modify compose file.
* Change to MediaBox directory
* docker-compose up -d docker-compose.yml
