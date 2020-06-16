# embyDocker

docker run -d --volume /home:/mnt/share1  --volume /media:/mnt/share2 --publish 2020:8096 --publish 2021:8920 --env UID=1000  --env GID=100  --env GIDLIST=100 --name=emby  emby/embyserver:latest
