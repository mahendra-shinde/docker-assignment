## MySQL Container image building

### Instructions

1. Create a Dockerfile to build a new MySQL Database image for database "orderdb"
2. Use the [orderdb.sql](./orderdb.sql) file inside "Dockerfile" build populate the database on startup.
3. Push the image to docker-hub registry and share your image name
    Example : mahendrshinde/assignment1
    NOTE: USE YOUR DOCKER_ID instead of `mahendrshinde`

Hints:

* Use base image `mysql:5.7`
* Database Namae `orderdb`
* Username & Password : As per your choice 