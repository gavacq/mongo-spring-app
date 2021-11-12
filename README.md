## Create a multi-stage docker image

To compile and package using Docker multi-stage builds

```bash
docker build . -t my-app
```

## Create a Docker image packaging an existing jar

```bash
./gradlew build
docker build . -t my-app -f Dockerfile.only-package
```

## To run the docker image

```bash
docker run -p 8080:8080 my-app
```

And then visit http://localhost:8080 in your browser.

## MongoDB
https://spring.io/guides/gs/accessing-data-mongodb/
https://www.linkedin.com/pulse/get-started-spring-boot-mongodb-docker-compose-saeid-farahi/

