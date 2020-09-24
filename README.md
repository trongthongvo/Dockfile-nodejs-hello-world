# Dockfile-nodejs-hello-world
#Example Dockerfile Node JS with hello world

docker build -t hello-world .
docker container run -p 4000:8081  hello-world
