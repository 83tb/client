# Dockerized Orisi Client

Smart contracts allows you to transform deals, laws, business logic or any other rules into code. 
Orisi is a platform that does smart contracts.
oracle project is a Docker/Container implementation of Orisi nodes.


More here -> https://github.com/orisi/wiki/wiki/Orisi-White-Paper

## Quick install

- If you have docker installed - running Orisi Oracle node is as easy as typing


```
docker pull orisi/client
```

```
docker run orisi/client > /dev/null &

```

Now you can ```docker inspect``` your container and login inside using ssh. 


That's all!


#### - If you don't have docker installed I prepared for you [super short Docker installation procedures](manual/docker_install.md), Linux, MacosX and Windows

### [Docker usage cheatsheet](manual/docker_basics.md)

## Building Orisi Docker Client Image from source

If you want to have everything installed from scratch you can just download the Dockerfile from the source:
```
git clone https://github.com/orisi/client.git
cd client
docker build -t client .
```

>Whole process should take around 20 minutes. Your mileage may vary.


