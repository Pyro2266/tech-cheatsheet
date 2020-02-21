# Technology cheatsheet

### Maven
* `clean install` - cleans and builds project
    * `-DskipTests=true` - skips tests
    * `-P <profile_name>` - runs with profile
### GIT

### Docker
* `docker ps` - show running containers
* `docker ps -a` - show all containers
* `docker images` - show images
* `docker inspect <container_name>` - show configuration and information about container (including network and IP addresses) 
* `docker exec -it <container_name> /bin/bash` - open console on running container
* `docker system prune` - clean up dangling (not associated with a container) resources (images, containers, volumes, networks)
* `docker system prune -a` - additionally remove any stopped containers and all unused images (not just dangling images)

### Sublime
* `alt + F3` - quick find all - selects all occurrences of selected part of text
* `ctrl + shift + L` - places cursor at the end of each selected line

### Linux
* `netstat` or `ss` - list open ports
    * `-n`, `--numeric` - don't resolve service names
    * `-l`, `--listening` - display listening sockets
    * `-t`, `--tcp` - display only TCP sockets
    * `-u`, `--udp` - display only UDP sockets
    * `-p`, `--processes` - show process using socket
* `sudo update-alternatives --config java` - change installed java version
    
