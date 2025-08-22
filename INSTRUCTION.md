#start service 
docker compose -f .\docker-compose.yml up -d
#stop service
docker compose -f .\docker-compose.yml down
#url
http://localhost:8080