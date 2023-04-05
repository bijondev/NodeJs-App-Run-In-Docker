# simple nodejs app run in docker

#DOCKER Command
Build Image
```
docker build -t bijon2dev/nodejs-image-demo .
```
#Show Images
```
docker images
```

#Remove images
```
Docker rmi [image name or id]
```

#run container
```
docker run --name nodejs-dc -p 80:8080 -d bijon2dev/nodejs-image-demo
docker run --rm --name nodejs-dc2 -p 9000:8080 -d bijon2dev/nodejs-image-demo
```

#Show All container
Docker ps -a

#Show Running Container
```
Docker ps
```

#Remove container
```
Docker rm [container name / id]
```


#docker force stop

```
sudo systemctl stop docker.socket
sudo systemctl stop docker
sudo systemctl restart docker
```
