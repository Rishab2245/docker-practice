#### Clean up the whole system with chache 
``` docker system prune  ```   
#### Build a docker file and create an image 
(execute the below command either from the same directory the docker file pesent in and from the different directory with the file path on the place of )

``` docker build -t <tag-name> . ``` 
#### Run a container from an image   
``` docker run -it --rm --init -p <host_port>:<container_port> <image_name> ``` 

#### Bind mount project with the docker container
```
docker run -it --init -p 3000:3000 -v "$(pwd)":/developer/nodejs/node-bind-mount-project app-bind-mount-node
```

