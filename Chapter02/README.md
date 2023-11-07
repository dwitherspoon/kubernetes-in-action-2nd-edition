# Kubernetes in Action, 2nd Edition

## Chapter 2. Understanding containers

### Creating the Kiada container image

Building the **`kiada:1.0`** image:
- [Makefile](kiada-0.1/Makefile) - contains commands to build and push the image
- [Dockerfile](kiada-0.1/Dockerfile) - Docker instructions for building the image
- [app.js](kiada-0.1/app.js) - application code (JavaScript)


```
docker build -t kiada:latest

docker run --name kiada-container -p 1234:8080 -d kiada
```
