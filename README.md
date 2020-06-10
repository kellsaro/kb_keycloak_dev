# kb_keycloak_dev
Keycloak 10.0.2 server configured for custom development

The configuration are based on Keycloak-containers[https://github.com/keycloak/keycloak-containers]

# Instructions
## Download, build and run

- Download or clone this repo
- In the console, go to the downloaded directory and type: `docker build --tag kb_keycloak_dev:1.0 .`
- Run: `docker run -p 8080:8080 --detach --name kb_keycloak kb_keycloak_dev:1.0`

## Run directly using docker
