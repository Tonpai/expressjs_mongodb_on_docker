# expressjs_mongodb_on_docker
```docker-compose``` is the way to run multiple container in single command. So, this project introducing simple way to set expressjs and mongodb in single file(docker-compose). 

## Starting
1. clone this project
2. run this command :
```
docker-compose up
```
if you want to terminate, use ```Ctrl+C```
## Addition
### Run container in background
if you want to run docker container in background you need to use this command:
```
docker-compose up -d
```
when you need to stop containers that is working you need to use this command:

```
docker-compose down
```