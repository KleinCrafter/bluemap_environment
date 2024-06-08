# Environment for Bluemap Setups
After starting the containers, you need to accept the download for bluemap.
`./data/minecraft/bluemap/core.conf`

## (Sub)domain
If you want BlueMap on a domain `http://www.example.com` or subdomain `http://bluemap.example.com` use this example:
Starting the containers: `docker compose -f docker-compose_domain.yml up -d`
Open in browser: (http://127.0.0.1:8080)[http://127.0.0.1:8080]

## Subdirectory
If you want BlueMap on a subdirectory `http://www.example.com/bluemap/` use this example:
Starting the containers: `docker compose -f docker-compose_directory.yml up -d`
Open in browser: (http://127.0.0.1:8080/bluemap/)[http://127.0.0.1:8080/bluemap/]