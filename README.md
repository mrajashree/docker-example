## How to run this app
1. `docker build -t py-example .`
This will create a docker image from the Dockerfile, called py-example. List it using the `docker images` command
2. `docker run -p 8080:80 py-example`
This will start a new container using the above image, list it using `docker ps` command

Access the app over <yourIP>:8080
