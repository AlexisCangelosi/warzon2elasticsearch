# On EC2 instance:
- install git & docker (https://docs.docker.com/engine/install/debian/)
- sysctl -w vm.max_map_count=262144
- Edit docker-compose.yml login & password

# Start
`docker-compose up -d`  
attend un peu que ES se lance  

`docker exec pythonwz pip install -r requirements.txt`  
`docker exec pythonwz python warzone.py`  
