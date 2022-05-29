```bash 
docker logs <container name>
# to stop a container 
docker kill 
# to remove the container 
docker rm 
# limit the memory or processing 
doker rum memory flags
```

### Manage Containers: 
Container Networking
```bash
# define port as we run 
docker run -p porthost:portcontainer
# find the port which it is running
docker port container 
```
Dockerfile 
ENTRYPOINT and CMD
ENTRYPOINT and CMD are same but CMD expects parameters

create docker image from the file: 
sudo docker build -t testimage18apr:v2 .
