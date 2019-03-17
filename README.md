# Docker VIT Demos & Presentations

Slide: https://www.slideshare.net/ajeetraina/introduction-to-docker-vellor-institute-of-technology

## Example #1:  Demonstrating Hello Whale Example


## Pulling Docker Image

```
$ docker pull ajeetraina/hellowhale
```


## Listing out Docker Images
```
$ docker image ls
```

## Running Docker Containers

```
$ docker run –d –p 5000:5000 –-name hellowhale ajeetraina/hellowhale
```

## Stopping the container
      
 ```
  docker stop hellowhale (or <container id>)
```


## Example #2 -  How to build Docker Whale Docker Image and push it to DockerHub?

## Cloning the Repository

```
git clone https://github.com/ajeetraina/hellowhale
cd hellowhale
```

## Building the Docker Image

```
docker build -t ajeetraina/hellowhale1 .
```

```
docker tag ajeetraina/hellowhale1 ajeetraina/cutewhale 
```

## Push it to DockerHub

```
docker login
```

```
docker push ajeetraina/cutewhale 
```

Time to Login to another instance and download it and run it.

## Create Visualizer








