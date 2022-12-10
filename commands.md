## Build docker image
- docker build -f Dockerfile -t hello-python:latest .

## Verify image was created
- docker image ls

## Have Docker run the application in a container and map it to port 5001 (check http://localhost:5001)
- docker run -p 5001:5000 hello-python