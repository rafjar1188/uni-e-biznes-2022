# Exercise 1

## Dockerfile-Kotlin

Dockerfile with Ubuntu and Kotlin installed using sdkman.

## Dockerfile-Python-PPA

Dockerfile with Ubuntu and Python installed using PPA.

## Dockerfile-Python-Source

Dockerfile with Ubuntu and Python installed from source.

## Additional info

### Building specific images

Using specific file name for image building:
```bash
docker build --file <$dockerfile_name> --tag <$image_name> <$context_location>
```

Using docker-compose for all image building:
```bash
docker-compose up
```

Creating containers for all services:
```bash
docker-compose create
```

### Creating initial gradle project

Using gradle for Kotlin based project:
```bash
gradle init --type kotlin-application --dsl kotlin --test-framework kotlintest --project-name project --package project --incubating
```

### Links

DockerHub Profile:
- https://hub.docker.com/u/rafjar1188

DockerHub Specific Images:
- https://hub.docker.com/r/rafjar1188/e-biznes-2022-kotlin
- https://hub.docker.com/r/rafjar1188/e-biznes-2022-python-ppa
- https://hub.docker.com/r/rafjar1188/e-biznes-2022-python-source
