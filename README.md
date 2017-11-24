# docker-NginxProxy-letsEncrypt

## requirement
install docker and docker-compose

## first start

`docker-compose up -d`

there you have a working Reverse proxy + let's encrypt setup

## add sub project

providing they have a docker-compose well setup (autonomous + network of "root_default")

for exemple : 
```
git clone https://github.com/PookMook/openRaid.git
cd openRaid
docker-compose up -d
```

### restart the proxy+certification process
Need to find a way to make it automatically

```
cd ..
docker-compose stop
docker-compose up -d
```
