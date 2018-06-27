## Delete
### Delete every Docker containers
Must be run first because images are attached to containers
```bash
docker rm -f $(docker ps -a -q)
```

### Delete every Docker image
```bash
docker rmi -f $(docker images -q)
```
