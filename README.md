# simple-reverse-proxy

**This application is a reverse proxy which redirect http request from {{host}}:8080/api/ to htpp://my-app:8080/**

## Installation

```
docker build -t simple-reverse-proxy .
```


## How run the application

```
docker run -it -dp 8080:8080 simple-reverse-proxy
```
