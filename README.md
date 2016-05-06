# Lab.Docker

References
* http://www.docker.com/ 
* https://github.com/docker 
* https://hub.docker.com/explore/
* https://docs.docker.com/windows/
* https://docs.docker.com/engine/userguide/intro/


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


Interesting Docker Contributors
* https://github.com/jfrazelle
	* https://blog.jessfraz.com/
* https://github.com/allingeek
	* http://allingeek.com/


Helpful Articles
* http://blog.pavelsklenar.com/5-useful-docker-tip-and-tricks-on-windows/



TroubleShooting
* Docker on Windows 10/
	* ```Docker Quickstart Terminal``` shortcut doesn’t work – the shortcut doesn’t run the start.sh script in a Bash shell.
	* FIX: Aassociate the .sh file extension with the ```<Git home>/bin/sh.exe``` program or some other Bash shell emulator for Windows.
	* Or, modify the target on the shortcust like this: ```C:\{your install path}\Git\bin\sh.exe --login -i "C:\{your install path}\DockerToolbox\start.sh"```

Tips
* Your Docker VM is listening on port 22, so you can directly connect to your running VM via SSH (using username: docker, password: tcuser).

