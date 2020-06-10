# kb_keycloak_dev

Keycloak 10.0.2 server configured for custom development

The configuration are based on Keycloak-containers[https://github.com/keycloak/keycloak-containers]

## Usage
**Download, build and run**

- Download or clone this repo
- In the console, go to the downloaded directory and type: `docker build --tag kb_keycloak_dev:1.0 .`
- Run: `docker run -p 8080:8080 --detach --name kb_keycloak_dev kb_keycloak_dev:1.0`
- Go to `http://localhost:8080`and use user `admin` with password `admin`

**Run directly using docker**
- In the console type: `docker run -p 8080:8080 --detach --name kb_keycloak_dev kellsaro/kb_keycloak_dev:latest`
