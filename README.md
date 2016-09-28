# Lab.Docker

References
* http://www.docker.com/ 
* https://github.com/docker 
* https://hub.docker.com/explore/
* https://docs.docker.com/windows/
* https://docs.docker.com/engine/userguide/intro/
* https://github.com/docker-training


Recommended Books
* [Docker Containers, Build and Deploy with Kubernetes, Flannel, Cockpit, and Atomic] (http://www.amazon.com/Docker-Containers-Content-Update-Program/dp/013413656X)
* [Dockere In Action] (https://www.manning.com/books/docker-in-action) 
	* https://github.com/dockerinaction 


Interesting Github Projects
* https://github.com/docker/docker-bench-security 
* https://github.com/jfrazelle/binctr
	* Fully static, unprivileged, self-contained, containers as executable binaries.
* [Datacenter Operating System, DC/OS] (https://github.com/dcos)
* https://github.com/samalba/dockerclient 
* https://github.com/Microsoft/Docker-PowerShell/
* https://github.com/docker-training/webapp
* https://github.com/docker-training/staticweb
* https://github.com/docker-training/docker-fundamentals-image
* https://github.com/docker/swarmkit


Interesting Docker Contributors
* https://github.com/jfrazelle
	* https://blog.jessfraz.com/
* https://github.com/allingeek
	* http://allingeek.com/


Deployment Tooling
* https://github.com/spotify/docker-maven-plugin


Helpful Articles
* http://blog.pavelsklenar.com/5-useful-docker-tip-and-tricks-on-windows/


Docker Related Blogs
* http://jpetazzo.github.io/


TroubleShooting
* Docker on Windows 10/
	* ```Docker Quickstart Terminal``` shortcut doesn’t work – the shortcut doesn’t run the start.sh script in a Bash shell.
	* FIX: Aassociate the .sh file extension with the ```<Git home>/bin/sh.exe``` program or some other Bash shell emulator for Windows.
	* Or, modify the target on the shortcust like this: ```C:\{your install path}\Git\bin\sh.exe --login -i "C:\{your install path}\DockerToolbox\start.sh"```


Tips
* List all docker images 
	* ```docker ps```
* Your Docker VM is listening on port 22, so you can directly connect to your running VM via SSH (using username: docker, password: tcuser).
* To pass a long-running command to test a docker image...(assumes your image is named 'fedora')
	* ```docker run -d fedora /bin/sh -c "while true; do echo hello world; sleep 1; done"``
* Stop all running commands
	* ```docker stop $(docker ps -a -q)```
* Attached to a running container
	* ```sudo docker exec -i -t {container id | container name} sh```
	



Interesting Articles
* https://medium.com/@adriaandejonge/moving-from-docker-to-rkt-310dc9aec938#.hr7dfpon2
* https://blog.docker.com/2016/09/build-your-first-docker-windows-server-container/

