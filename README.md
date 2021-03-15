# vanilla-vue

Dockerized default Vue application.

Chris Groleau 3/14/2021

Docker version 20.10.2, build 2291f61

### To run from Docker Hub
```
docker run -p 8080:8080 cagroleau/vanilla-vue
```

### to build and run locally
```
cd vanilla-vue

docker build -t vanilla-vue .

docker run -p 8080:8080 vanilla-vue
```
#container will serve application to port 8080 on localhost.
