# Docker Commands
## docker ps
### - shows running containers
## docker ps --all
### - shows all containers (running and stopped)
## docker run [image] 
![alt text](./images/image-3.png)
![alt text](./images/image.png)

## docker run [image] command
![alt text](./images/image-1.png)
![alt text](./images/image-2.png)

## docker create [image]

## docker start [container id]
### - starts the container
### - does not wait for output 
### - works on stopped containers also

## docker start -a [container id]
### - waits for output (shows in terminal)

## docker system prune
### deletes:
### - all stoped containers build cache 
### - all networks not used by at least one container
### - all dangling images
### - all build cache

## docker logs [container id]
- returns all of the logs from the container
![alt text](./images/image-4.png)

## docker stop [container id]
### - takes a couple of seconds to shutdown
### - does a litte bit of cleanup
### - if it takes more than 10 seconds to shutdown, docker autoamtically executes the kill command 
![alt text](./images/image-5.png)
## docker kill [container id]
### - shutdowns the container immediately
![alt text](./images/image-6.png)
