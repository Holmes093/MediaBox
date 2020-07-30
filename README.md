<p align="center">
  <img src="./MediaBox.png" width="450" />
</p>
<h1 align="center">
  MediaBox
</h1>

<p align="center">
  MediaBox is a Docker-Compose file consiting of all the relevant components to setup your own Media Server.
</p>

## Includes
* Traefik - Reverse Proxy for all services
* Watchtower - Pull Container images autoamtically 
* Portainer - Container management UI
* Plex - Media Server
* Sonarr - TV Show management utility
* Radarr - Movie management utility
* Deluge - Torrent download client
* Ombi - Request platform for Shows & Movies
* Tautulli - Plex monitoring utility
* Cardigann - Index Utility
* TV Headend - TV streaming server

## Requirements
* Docker
* Docker-Compose

## Instructions 
* Clone Repo to ~/docker
* Modify .env file
* Modify compose file.
* Change to MediaBox directory
* docker-compose up -d docker-compose.yml
