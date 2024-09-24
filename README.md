# Check docker image
docker images

# How to run nestjs application
docker run -p host-port:container-port image-name:tag
## Example: 
docker run -p 8080:3000 nest-docker:dev
### You will find it on your machine localhost:8080