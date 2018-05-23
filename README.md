## Dockerfile Node.js Web Apps

### Development

#### Build images

```
docker build -t node-docker-dev .
```

#### Run container

```
docker run --rm -it -p 8080:8080 -v $(pwd):/app \node-docker-dev
```