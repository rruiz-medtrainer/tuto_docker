## Build the image
```console
docker build -f flask-docker-tutorial:latest .
```

## Run container
```console
docker run -d  -p 5000:5000 flask-docker-tutorial
```

Go to localhost:5000 in the browser
