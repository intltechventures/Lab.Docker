
Docker Tips
====


General Commands
* ```docker --version```
* ```docker info```


Docker image commands
* ```docker run {image name}```
* ```docker image ls```

Docker Container commands
* ```docker container --help```
* ```docker container ls```
* ```docker container ls --all```

Explore attributes of a container
* ```ocker inspect <container id>```

Find the IP Address of a container
* ```docker inspect <container id> | grep "IPAddress"```
* ```docker exec stupefied_babbage cat /etc/hosts```
