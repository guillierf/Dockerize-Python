# Dockerizing a Python app

## Procedure

Build Docker image:

```
$ cd Build-Docker

$ docker build . -t <your username>/identidock
```

Run a container using the image:
```
$ docker run -d -p 5000:5000 <your username>/identidock
```

Check the app:
```
$ curl localhost:5000
 ```
