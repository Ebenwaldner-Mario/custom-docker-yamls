# custom-docker-yamls
Collection of some of my docker-compose files to keep easily available if needed again. Some have heavy custom configurations, some others are just the provided docker-compose files by the image creators.
An illustration of my personal home network structure can be found [here](https://github.com/Ebenwaldner-Mario/custom-docker-yamls/edit/main/home-network.svg)

# My hosting list
My personal must haves to build up a reliable home system. I recommend running as much as possible in docker containers to increase security and easen managment.

## Machine managment
- Portainer
- Cockpit (General bare bones linux managment)
- Watchtower (Keeping docker containers automatically up to date)
- Borgmatic (Crontab based backups with lz4 compression)
- Homepage (Ease monitoring and link managment)

## Networking
- PiHole (DHCP and DNS server)
- NGINX Reverse Proxy
- Wireguard VPN (wg-easy)

## Development
- Synapse (Matrix based backend server for E2EE based communcation)
- Gitlab-CE
- Ollama
- Open-WebUI
- Jenkins
- Jenkins Inbound Agent (remote)

## Media
- Immich
- Navidrome
- Mealie
- Vaultwarden
- Feishin
- Metube
- Nextcloud AIO
