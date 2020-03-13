# README

## Origin
[jbossdemocentral/rhpam7-install-demo](https://github.com/jbossdemocentral/rhpam7-install-demo)

## How to build
```
docker build --no-cache -t rhpam7 .
```
	
## Run
```
docker run -it -p 8080:8080 -p 9990:9990 rhpam7
```

## Access
### [Business Central](http://localhost:8080/business-central)
#### Username
pamAdmin
#### Password
redhatpam1!

### [Sample Case Management App](http://localhost:8080/rhpam-case-mgmt-showcase)
#### Username
pamAdmin
#### Password
redhatpam1!

### Docker Hub
[chriswongatcuhk/rhpam7](https://hub.docker.com/repository/docker/chriswongatcuhk/rhpam7)
