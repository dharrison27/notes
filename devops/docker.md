[Zacker]: # 'Zacker, Craig. _Installation, Storage and Compute with Windows Server 2016: Exam Ref 70-740_. 2017'
[pluralsight:70-740-containers]: https://app.pluralsight.com/library/courses/windows-server-2016-containers-implementing/table-of-contents "Implementing Containers on Windows Server 2016"
[udemy]: https://www.udemy.com/course/docker-mastery-for-nodejs/ "Docker for Node.js Projects From a Docker Captain"


# Docker
Docker **repositories** are associated with a single image, various versions of which can be specified with a **tag**.

#### Docker on Windows
Docker has traditionally distributed its own Linux kernel to use with **Docker Desktop**.
After announcing in June of 2019 that Docker would begin working with **Windows Subsystem for Linux**, in March of 2020 Docker released a Technical Preview of Docker that included support for running on WSL 2.

The Technical Preview requires <sup>[code.visualstudio.com](https://code.visualstudio.com/blogs/2020/03/02/docker-in-wsl2 "Using Docker in WSL 2")</sup>
- Windows 10 Insider Preview build 18975 or later
- WSL 2 running Ubuntu
- the **Remote - WSL** extension for VS Code

# `docker` syntax
###### Command groups
[docker:attach]: https://docs.docker.com/engine/reference/commandline/attach/ "docker attach"
[docker:build]: https://docs.docker.com/engine/reference/commandline/build/ "docker build"
[docker:builder]: https://docs.docker.com/engine/reference/commandline/builder/ "docker builder"
[docker:checkpoint]: https://docs.docker.com/engine/reference/commandline/checkpoint/ "docker checkpoint"
[docker:commit]: https://docs.docker.com/engine/reference/commandline/commit/ "docker commit"
[docker:config]: https://docs.docker.com/engine/reference/commandline/config/ "docker config"
[docker:container]: https://docs.docker.com/engine/reference/commandline/container/ "docker container"
[docker:context]: https://docs.docker.com/engine/reference/commandline/context/ "docker context"
[docker:cp]: https://docs.docker.com/engine/reference/commandline/cp/ "docker cp"
[docker:create]: https://docs.docker.com/engine/reference/commandline/create/ "docker create"
[docker:diff]: https://docs.docker.com/engine/reference/commandline/diff/ "docker diff"
[docker:events]: https://docs.docker.com/engine/reference/commandline/events/ "docker events"
[docker:exec]: https://docs.docker.com/engine/reference/commandline/exec/ "docker exec"
[docker:export]: https://docs.docker.com/engine/reference/commandline/export/ "docker export"
[docker:history]: https://docs.docker.com/engine/reference/commandline/history/ "docker history"
[docker:image]: https://docs.docker.com/engine/reference/commandline/image/ "docker image"
[docker:images]: https://docs.docker.com/engine/reference/commandline/images/ "docker images"
[docker:import]: https://docs.docker.com/engine/reference/commandline/import/ "docker import"
[docker:info]: https://docs.docker.com/engine/reference/commandline/info/ "docker info"
[docker:inspect]: https://docs.docker.com/engine/reference/commandline/inspect/ "docker inspect"
[docker:kill]: https://docs.docker.com/engine/reference/commandline/kill/ "docker kill"
[docker:load]: https://docs.docker.com/engine/reference/commandline/load/ "docker load"
[docker:login]: https://docs.docker.com/engine/reference/commandline/login/ "docker login"
[docker:logout]: https://docs.docker.com/engine/reference/commandline/logout/ "docker logout"
[docker:logs]: https://docs.docker.com/engine/reference/commandline/logs/ "docker logs"
[docker:manifest]: https://docs.docker.com/engine/reference/commandline/manifest/ "docker manifest"
[docker:network]: https://docs.docker.com/engine/reference/commandline/network/ "docker network"
[docker:node]: https://docs.docker.com/engine/reference/commandline/node/ "docker node"
[docker:pause]: https://docs.docker.com/engine/reference/commandline/pause/ "docker pause"
[docker:plugin]: https://docs.docker.com/engine/reference/commandline/plugin/ "docker plugin"
[docker:port]: https://docs.docker.com/engine/reference/commandline/port/ "docker port"
[docker:ps]: https://docs.docker.com/engine/reference/commandline/ps/ "docker ps"
[docker:pull]: https://docs.docker.com/engine/reference/commandline/pull/ "docker pull"
[docker:push]: https://docs.docker.com/engine/reference/commandline/push/ "docker push"
[docker:rename]: https://docs.docker.com/engine/reference/commandline/rename/ "docker rename"
[docker:restart]: https://docs.docker.com/engine/reference/commandline/restart/ "docker restart"
[docker:rm]: https://docs.docker.com/engine/reference/commandline/rm/ "docker rm"
[docker:rmi]: https://docs.docker.com/engine/reference/commandline/rmi/ "docker rmi"
[docker:run]: https://docs.docker.com/engine/reference/commandline/run/ "docker run"
[docker:save]: https://docs.docker.com/engine/reference/commandline/save/ "docker save"
[docker:search]: https://docs.docker.com/engine/reference/commandline/search/ "docker search"
[docker:secret]: https://docs.docker.com/engine/reference/commandline/secret/ "docker secret"
[docker:service]: https://docs.docker.com/engine/reference/commandline/service/ "docker service"
[docker:stack]: https://docs.docker.com/engine/reference/commandline/stack/ "docker stack"
[docker:start]: https://docs.docker.com/engine/reference/commandline/start/ "docker start"
[docker:stats]: https://docs.docker.com/engine/reference/commandline/stats/ "docker stats"
[docker:stop]: https://docs.docker.com/engine/reference/commandline/stop/ "docker stop"
[docker:swarm]: https://docs.docker.com/engine/reference/commandline/swarm/ "docker swarm"
[docker:system]: https://docs.docker.com/engine/reference/commandline/system/ "docker system"
[docker:tag]: https://docs.docker.com/engine/reference/commandline/tag/ "docker tag"
[docker:top]: https://docs.docker.com/engine/reference/commandline/top/ "docker top"
[docker:trust]: https://docs.docker.com/engine/reference/commandline/trust/ "docker trust"
[docker:unpause]: https://docs.docker.com/engine/reference/commandline/unpause/ "docker unpause"
[docker:update]: https://docs.docker.com/engine/reference/commandline/update/ "docker update"
[docker:version]: https://docs.docker.com/engine/reference/commandline/version/ "docker version"
[docker:volume]: https://docs.docker.com/engine/reference/commandline/volume/ "docker volume"
[docker:wait]: https://docs.docker.com/engine/reference/commandline/wait/ "docker wait"

[docker attach]: #docker-attach '```&#10;$ docker attach&#10;```&#10;Attach local standard input, output, and error streams to a running container'
[docker build]: #docker-build '```&#10;$ docker build&#10;```&#10;Build an image from a Dockerfile'
[docker builder]: #docker-builder '```&#10;$ docker builder&#10;```&#10;Manage builds'
[docker checkpoint]: #docker-checkpoint '```&#10;$ docker checkpoint&#10;```&#10;Manage checkpoints'
[docker commit]: #docker-commit '```&#10;$ docker commit&#10;```&#10;Create a new image from a container’s changes'
[docker config]: #docker-config '```&#10;$ docker config&#10;```&#10;Manage Docker configs'
[docker container]: #docker-container '```&#10;$ docker container&#10;```&#10;Manage containers'
[docker context]: #docker-context '```&#10;$ docker context&#10;```&#10;Manage contexts'
[docker cp]: #docker-cp '```&#10;$ docker cp&#10;```&#10;Copy files/folders between a container and the local filesystem'
[docker create]: #docker-create '```&#10;$ docker create&#10;```&#10;Create a new container'
[docker diff]: #docker-diff '```&#10;$ docker diff&#10;```&#10;Inspect changes to files or directories on a container’s filesystem'
[docker events]: #docker-events '```&#10;$ docker events&#10;```&#10;Get real time events from the server'
[docker exec]: #docker-exec '```&#10;$ docker exec&#10;```&#10;Run a command in a running container'
[docker export]: #docker-export '```&#10;$ docker export&#10;```&#10;Export a container’s filesystem as a tar archive'
[docker history]: #docker-history '```&#10;$ docker history&#10;```&#10;Show the history of an image'
[docker image]: #docker-image '```&#10;$ docker image&#10;```&#10;Manage images'
[docker images]: #docker-images '```&#10;$ docker images&#10;```&#10;List images'
[docker import]: #docker-import '```&#10;$ docker import&#10;```&#10;Import the contents from a tarball to create a filesystem image'
[docker info]: #docker-info '```&#10;$ docker info&#10;```&#10;Display system-wide information'
[docker inspect]: #docker-inspect '```&#10;$ docker inspect&#10;```&#10;Return low-level information on Docker objects'
[docker kill]: #docker-kill '```&#10;$ docker kill&#10;```&#10;Kill one or more running containers'
[docker load]: #docker-load '```&#10;$ docker load&#10;```&#10;Load an image from a tar archive or STDIN'
[docker login]: #docker-login '```&#10;$ docker login&#10;```&#10;Log in to a Docker registry'
[docker logout]: #docker-logout '```&#10;$ docker logout&#10;```&#10;Log out from a Docker registry'
[docker logs]: #docker-logs '```&#10;$ docker logs&#10;```&#10;Fetch the logs of a container'
[docker manifest]: #docker-manifest '```&#10;$ docker manifest&#10;```&#10;Manage Docker image manifests and manifest lists'
[docker network]: #docker-network '```&#10;$ docker network&#10;```&#10;Manage networks'
[docker node]: #docker-node '```&#10;$ docker node&#10;```&#10;Manage Swarm nodes'
[docker pause]: #docker-pause '```&#10;$ docker pause&#10;```&#10;Pause all processes within one or more containers'
[docker plugin]: #docker-plugin '```&#10;$ docker plugin&#10;```&#10;Manage plugins'
[docker port]: #docker-port '```&#10;$ docker port&#10;```&#10;List port mappings or a specific mapping for the container'
[docker ps]: #docker-ps '```&#10;$ docker ps&#10;```&#10;List containers'
[docker pull]: #docker-pull '```&#10;$ docker pull&#10;```&#10;Pull an image or a repository from a registry'
[docker push]: #docker-push '```&#10;$ docker push&#10;```&#10;Push an image or a repository to a registry'
[docker rename]: #docker-rename '```&#10;$ docker rename&#10;```&#10;Rename a container'
[docker restart]: #docker-restart '```&#10;$ docker restart&#10;```&#10;Restart one or more containers'
[docker rm]: #docker-rm '```&#10;$ docker rm&#10;```&#10;Remove one or more containers'
[docker rmi]: #docker-rmi '```&#10;$ docker rmi&#10;```&#10;Remove one or more images'
[docker run]: #docker-run '```&#10;$ docker run&#10;```&#10;Run a command in a new container'
[docker save]: #docker-save '```&#10;$ docker save&#10;```&#10;Save one or more images to a tar archive (streamed to STDOUT by default)'
[docker search]: #docker-search '```&#10;$ docker search&#10;```&#10;Search the Docker Hub for images'
[docker secret]: #docker-secret '```&#10;$ docker secret&#10;```&#10;Manage Docker secrets'
[docker service]: #docker-service '```&#10;$ docker service&#10;```&#10;Manage services'
[docker stack]: #docker-stack '```&#10;$ docker stack&#10;```&#10;Manage Docker stacks'
[docker start]: #docker-start '```&#10;$ docker start&#10;```&#10;Start one or more stopped containers'
[docker stats]: #docker-stats '```&#10;$ docker stats&#10;```&#10;Display a live stream of container(s) resource usage statistics'
[docker stop]: #docker-stop '```&#10;$ docker stop&#10;```&#10;Stop one or more running containers'
[docker swarm]: #docker-swarm '```&#10;$ docker swarm&#10;```&#10;Manage Swarm'
[docker system]: #docker-system '```&#10;$ docker system&#10;```&#10;Manage Docker'
[docker tag]: #docker-tag '```&#10;$ docker tag&#10;```&#10;Create a tag TARGET_IMAGE that refers to SOURCE_IMAGE'
[docker top]: #docker-top '```&#10;$ docker top&#10;```&#10;Display the running processes of a container'
[docker trust]: #docker-trust '```&#10;$ docker trust&#10;```&#10;Manage trust on Docker images'
[docker unpause]: #docker-unpause '```&#10;$ docker unpause&#10;```&#10;Unpause all processes within one or more containers'
[docker update]: #docker-update '```&#10;$ docker update&#10;```&#10;Update configuration of one or more containers'
[docker version]: #docker-version '```&#10;$ docker version&#10;```&#10;Show the Docker version information'
[docker volume]: #docker-volume '```&#10;$ docker volume&#10;```&#10;Manage volumes'
[docker wait]: #docker-wait '```&#10;$ docker wait&#10;```&#10;Block until one or more containers stop, then print their exit codes'

[`attach`][docker attach]<sup>[?][docker:attach]</sup>
[`build`][docker build]<sup>[?][docker:build]</sup>
[`builder`][docker builder]<sup>[?][docker:builder]</sup>
[`checkpoint`][docker checkpoint]<sup>[?][docker:checkpoint]</sup>
[`commit`][docker commit]<sup>[?][docker:commit]</sup>
[`config`][docker config]<sup>[?][docker:config]</sup>
[`container`][docker container]<sup>[?][docker:container]</sup>
[`context`][docker context]<sup>[?][docker:context]</sup>
[`cp`][docker cp]<sup>[?][docker:cp]</sup>
[`create`][docker create]<sup>[?][docker:create]</sup>
[`diff`][docker diff]<sup>[?][docker:diff]</sup>
[`events`][docker events]<sup>[?][docker:events]</sup>
[`exec`][docker exec]<sup>[?][docker:exec]</sup>
[`export`][docker export]<sup>[?][docker:export]</sup>
[`history`][docker history]<sup>[?][docker:history]</sup>
[`image`][docker image]<sup>[?][docker:image]</sup>
[`images`][docker images]<sup>[?][docker:images]</sup>
[`import`][docker import]<sup>[?][docker:import]</sup>
[`info`][docker info]<sup>[?][docker:info]</sup>
[`inspect`][docker inspect]<sup>[?][docker:inspect]</sup>
[`kill`][docker kill]<sup>[?][docker:kill]</sup>
[`load`][docker load]<sup>[?][docker:load]</sup>
[`login`][docker login]<sup>[?][docker:login]</sup>
[`logout`][docker logout]<sup>[?][docker:logout]</sup>
[`logs`][docker logs]<sup>[?][docker:logs]</sup>
[`manifest`][docker manifest]<sup>[?][docker:manifest]</sup>
[`network`][docker network]<sup>[?][docker:network]</sup>
[`node`][docker node]<sup>[?][docker:node]</sup>
[`pause`][docker pause]<sup>[?][docker:pause]</sup>
[`plugin`][docker plugin]<sup>[?][docker:plugin]</sup>
[`port`][docker port]<sup>[?][docker:port]</sup>
[`ps`][docker ps]<sup>[?][docker:ps]</sup>
[`pull`][docker pull]<sup>[?][docker:pull]</sup>
[`push`][docker push]<sup>[?][docker:push]</sup>
[`rename`][docker rename]<sup>[?][docker:rename]</sup>
[`restart`][docker restart]<sup>[?][docker:restart]</sup>
[`rm`][docker rm]<sup>[?][docker:rm]</sup>
[`rmi`][docker rmi]<sup>[?][docker:rmi]</sup>
[`run`][docker run]<sup>[?][docker:run]</sup>
[`save`][docker save]<sup>[?][docker:save]</sup>
[`search`][docker search]<sup>[?][docker:search]</sup>
[`secret`][docker secret]<sup>[?][docker:secret]</sup>
[`service`][docker service]<sup>[?][docker:service]</sup>
[`stack`][docker stack]<sup>[?][docker:stack]</sup>
[`start`][docker start]<sup>[?][docker:start]</sup>
[`stats`][docker stats]<sup>[?][docker:stats]</sup>
[`stop`][docker stop]<sup>[?][docker:stop]</sup>
[`swarm`][docker swarm]<sup>[?][docker:swarm]</sup>
[`system`][docker system]<sup>[?][docker:system]</sup>
[`tag`][docker tag]<sup>[?][docker:tag]</sup>
[`top`][docker top]<sup>[?][docker:top]</sup>
[`trust`][docker trust]<sup>[?][docker:trust]</sup>
[`unpause`][docker unpause]<sup>[?][docker:unpause]</sup>
[`update`][docker update]<sup>[?][docker:update]</sup>
[`version`][docker version]<sup>[?][docker:version]</sup>
[`volume`][docker volume]<sup>[?][docker:volume]</sup>
[`wait`][docker wait]<sup>[?][docker:wait]</sup>
##### `docker attach`
Connect to a session on a running container <sup>[Zacker][Zacker]: 279</sup>
```sh
docker attach $CONTID
```
##### `docker build`
[docker build -&#116;]: #docker-build '```&#10;$ docker build -t&#10;$ docker build --tag&#10;```&#10;Name and optionally a tag in the "name:tag" format'

<code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> [`t`][docker build -&#116;] <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> 

Build a Docker image from a Dockerfile in the present working directory <sup>[PluralSight][pluralsight:70-740-containers]</sup>
```sh
docker build -t web .
```
##### `docker commit`
Save changes made to a modified container to a new image <sup>[Zacker][Zacker]: 279</sup>
```sh
docker commit $CONTID $USER/$CONT
```
##### `docker container`
[docker container commit]:                        #docker-container              '```&#10;$ docker container commit $CONTAINERID&#10;```&#10;Save container as a new, custom image'
[docker container diff]:                          #docker-container              '```&#10;$ docker container diff $CONTAINERID&#10;```&#10;Display all files added to or removed from base image'
[docker container ls]:                            #docker-container              '```&#10;$ docker container ls&#10;```&#10;'

[`commit`][docker container commit] 
[`diff`][docker container diff] 
[`ls`][docker container ls] 
##### `docker image`
[docker image build]:                         #docker-image                  '```&#10;$ docker image build&#10;```&#10;Create Docker image named '
[docker image tag]:                           #docker-image                  '```&#10;$ docker image tag $IMAGEID $TAG&#10;```&#10;Tag a container image'

[`build`][docker image build] 
[`tag`][docker image tag] 

Create docker image named "hello" with tag "v0.1" from contents of current directory
```
docker image build -t hello:v0.1 . | 
```
##### `docker network`
[docker network connect]: #docker-network-connect '```&#10;$ docker network connect&#10;```&#10;Connect a container to a network'
[docker network create]: #docker-network-create '```&#10;$ docker network create&#10;```&#10;Create a network'
[docker network disconnect]: #docker-network-disconnect '```&#10;$ docker network disconnect&#10;```&#10;Disconnect a container from a network'
[docker network inspect]: #docker-network-inspect '```&#10;$ docker network inspect&#10;```&#10;Display detailed information on one or more networks'
[docker network ls]: #docker-network-ls '```&#10;$ docker network ls&#10;```&#10;List networks'
[docker network prune]: #docker-network-prune '```&#10;$ docker network prune&#10;```&#10;Remove all unused networks'
[docker network rm]: #docker-network-rm '```&#10;$ docker network rm&#10;```&#10;Remove one or more networks'

[`connect`][docker network connect] 
[`create`][docker network create] 
[`disconnect`][docker network disconnect] 
[`inspect`][docker network inspect] 
[`ls`][docker network ls] 
[`prune`][docker network prune] 
[`rm`][docker network rm] 

Container networks can use various drivers, which are associated with specific key-value pairs in `daemon.json`:
- **NAT**: containers reside in their own network and the host acts as gateway and set with `{ "fixed-cidr" : "10.0.0.0/24" }`.
- **Transparent**: containers are assigned IP addresses on the same physical network to which the host belongs (similar to **External** virtual switches in Hyper-V), set with `{ "bridge": "none" }`.

Create a new network using the **transparent driver** <sup>[Zacker][Zacker]: 285</sup>
```sh
docker network create -d transparent $NETWORKNAME
```
Create a transparent network with static IP addresses
```sh
docker network create -d transparent --subnet=10.0.0.0/24 --gateway=10.0.0.1 $NETWORK
```
##### `docker ps`
Display a list of all running containers <sup>[Zacker][Zacker]: 278</sup>
```sh
docker ps -a
```
##### `docker rm`
Remove a container completely (must be stopped, unless `-f` is used) <sup>[Zacker][Zacker]: 279</sup>
```sh
docker rm $CONTID
```
##### `docker rmi`
Can be used to remove extraneous tags
##### `docker run`
[docker run -&#105;]: #docker-run '```&#10;$ docker run -i&#10;$ docker run --interactive&#10;```&#10;Keep STDIN open even if not attached&#10;Zacker, Craig. _Installation, Storage and Compute with Windows Server 2016: Exam Ref 70-740_. 2017: 274'
[docker run -&#116;]: #docker-run '```&#10;$ docker run -t&#10;$ docker run --tty&#10;```&#10;Allocate a pseudo-TTY&#10;Zacker, Craig. _Installation, Storage and Compute with Windows Server 2016: Exam Ref 70-740_. 2017: 274'
[docker run -&#100;]: #docker-run '```&#10;$ docker run -d&#10;$ docker run --detach&#10;```&#10;Run container in background and print container ID'
[docker run -&#112;]: #docker-run '```&#10;$ docker run -p $HOSTPORT:$CONTPORT&#10;$ docker run --publish $HOSTPORT:$CONTPORT&#10;```&#10;Publish a container port to the host port'
[docker run -&#118;]: #docker-run '```&#10;$ docker run -v $HOSTPATH:$CONTAINERPATH&#10;$ docker run --volume $HOSTPATH:$CONTAINERPATH&#10;```&#10;Bind-mount a volume.'
[docker run -&#109;]: #docker-run '```&#10;$ docker run -m&#10;$ docker run --memory&#10;```&#10;Limit memory'
[docker run --cpu-percent]: #docker-run '```&#10;$ docker run --cpu-percent&#10;```&#10;CPU percent (Windows only)'
[docker run --network]: #docker-run '```&#10;$ docker run --network&#10;```&#10;Connect a container to a network'
[docker run --volumes-from]: #docker-run '```&#10;$ docker run --volumes-from&#10;```&#10;Mount volumes from the specified container(s)'

<code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> [`d`][docker run -&#100;] <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> [`i`][docker run -&#105;] <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> [`m`][docker run -&#109;] <code>&nbsp;</code> <code>&nbsp;</code> [`p`][docker run -&#112;] <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> [`t`][docker run -&#116;] <code>&nbsp;</code> [`v`][docker run -&#118;] <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code>\
[`cpu-percent`][docker run --cpu-percent]
[`network`][docker run --network]
[`volumes-from`][docker run --volumes-from]

Create a Hyper-V container <sup>[Zacker][Zacker]: 275</sup>
```sh
docker run -it --isolation=hyperv microsoft/windowsservercore powershell
```
Bind port 80 of the container to port 8080 of the host <sup>[Zacker][Zacker]: 284</sup>
```sh
docker run -it -p 8080:80 microsoft/windowsservercore powershell
```
Create a container with a static IP address on the network you created
```sh
docker run -it --network=$NETWORK --ip=10.0.0.16 --dns=10.0.0.10 microsoft/windowsservercore powershell
```
##### `docker start`
Start a stopped container <sup>[Zacker][Zacker]: 278</sup>
```sh
docker start $CONTID
```
##### `docker stop`
Stop a container <sup>[Zacker][Zacker]: 278</sup>
```sh
docker stop $CONTID
```
##### `docker tag`
`docker tag` can be used to rename images and to prepare them to be [pushed][docker push] to a repository.

Tag an image on local container host <sup>[Zacker][Zacker]: 272</sup>
```sh
docker tag $USERNAME/$IMAGENAME:$TAG
```
##### `docker volume`
Docker has several options for containers to store files in a persistent manner:
- **Volumes** are stored in a part of the host filesystem which is managed by Docker (/var/lib/docker/volumes/ on Docker).
- **Bind mounts** may be stored anywhere on the host system and are specified by [`docker run --volume`][docker run -&#118;].
- **`tmpfs` mounts** are stored in the host system's memory only, and are available only on Linux.

Display data volumes <sup>[PluralSight][pluralsight:70-740-containers]</sup>
```sh
docker volume ls
```
# Dockerfile syntax
A Docker image consists of read-only **layers**, each of which represents an **instruction** that incrementally the changes the image being built up. 
Using [`docker build`][docker build], Dockerfiles can be used to construct new images.
The build process can be optimized by placing multiple commands in the same `RUN` instruction.
Dockerfiles are named simply "Dockerfile" with no extension or variation.
```dockerfile
FROM alpine
RUN apk update && apk add nodejs
COPY . /app
WORKDIR /app
CMD ["node","index.js"]
```
[Zacker][Zacker]: 289
```dockerfile
FROM microsoft/windowsservercore
RUN powershell -command install-windowsfeature dhcp -includemanagementtools
RUN powershell -configurationname microsoft.powershell -command add-dhcpserverv4scope -state active -activatepolicies $true -name scopetest -startrange 10.0.0.100 -endrange 10.0.0.200 -subnetmask 255.255.255.0
RUN md boot
COPY ./bootfile.wim c:/boot/
CMD powershell
```
[PluralSight][pluralsight:70-740-containers]
```dockerfile
FROM microsoft/windowsservercore
MAINTAINER @mike_pfeiffer
RUN powershell.exe -Command Install-WindowsFeature Web-Server
COPY ./websrc c:/inetpub/wwwroot
CMD [ "powershell" ]
```
# `docker-compose`
`up`
`down`
`-d`
`-v`

- separate binary coded in Python, available through `pip`
- can be used from the CLI as well as from YAML files ("compose file")
- can be used as a replacement for the normal `docker` CLI
- intended for use in developer workflows to avoid shell scripts that would typically be used to facilitate long command-line `docker` invocations
- not intended for production, for which Docker Swarm is preferable
- v2 is focused on development or testing with a single node
- v3 is focused on multi-node orchestration features

Simple Docker compose file <sup>[udemy.com][udemy]
```yaml
version: '2.0'

services:
  web:
    image: sample-01
    build: .
    ports:
      - '3000:3000'
```

```sh
docker-compose up -d
```
Bring everything down
```sh
docker-compose down -v
```
