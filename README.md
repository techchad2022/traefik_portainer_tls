# Traefik + Portainer + Cloudflare + Lets Encrypt
Install traefik and portainer.
Generate wildcard certificate using Let's Encrypt and Cloudflare.

## Before Installation
Changes to be made in docker-compose.yml:
- replace .example.com with your domain name.
- update CF_API_EMAIL= and CF_API_KEY= with the information obtained from cloudflare.

## Installation
> docker-compose up -d

## Uninstalling 
> docker-compose down

## Author
> name: techchad2022
  email: techchad2022@gmail.com


