# ubuntu-nginx

### 1. hub 에서 ubuntu pull & run
```
$ sudo docker pull ubuntu:22.04
[sudo] password for jsmin630:
22.04: Pulling from library/ubuntu
57c139bbda7e: Pull complete
Digest: sha256:e9569c25505f33ff72e88b2990887c9dcf230f23259da296eb814fc2b41af999
Status: Downloaded newer image for ubuntu:22.04
docker.io/library/ubuntu:22.04

$ sudo docker run -it --name utuntu-nginx ubuntu:22.04
```

### 2. nginx 설치
```
root@fe2b323ace45:/# apt update
root@fe2b323ace45:/# apt install nginx
```