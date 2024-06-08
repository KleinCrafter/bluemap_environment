# Environment for Bluemap Setups
This Repository contains _examples_ for bluemap installations using Docker for simple testing, this is not production ready!

After starting a project, you need to accept the download for bluemap. [Installation](https://bluemap.bluecolored.de/wiki/getting-started/Installation.html#steps)

## Traefik
Using [Traefik](https://doc.traefik.io/traefik/) 

### (Sub)domain
If you want BlueMap on a domain `http://www.example.com` or subdomain `http://bluemap.example.com`

`docker compose -f docker-compose_domain.yml up -d`

Open in browser: [http://127.0.0.1:8080](http://127.0.0.1:8080)

### Subdirectory
If you want BlueMap on a subdirectory `http://www.example.com/bluemap/`

`docker compose -f docker-compose_directory.yml up -d`

Open in browser: [http://127.0.0.1:8080/bluemap/](http://127.0.0.1:8080/bluemap/)
