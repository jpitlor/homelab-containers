# Homelab Containers

Docker Compose configurations for all of my container-based homelab services

## Usage

Use standard `docker compose` commands to start services

```shell
cd <service to start>
docker compose up -d
```

Alternatively, to start all services:

```shell
for folder in .; do
  cd folder
  docker compose up -d
  cd ..
done
```

## Exposed Ports

This repository will expose a number of ports to the internet:

- 443 (HTTPS traffic)
- 80 (HTTP traffic)
- TODO fill in other ports
