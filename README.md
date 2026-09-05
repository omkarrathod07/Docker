# Docker
This Repository is for sample code. All file must run in different folder.

## Docker Components:-- 
- FROM :- base OS
- RUN :- Execute shell Commands at time of build
- MAINTAINER :- Owner
- COPY :- Copy something from host to container
- ADD :- Copy somthing for internet
- EXPOSE :- Expose Post
- WORKDIR :- ---------------------

## Dockek Command:--
1. Create image from dockerfile 
```sh
docker build -t jenkins
```
2. Create container from image
```sh
docker run -it -name nginx01 -p 8080:8080 jenkins /bin/nash
```

---