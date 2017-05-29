# Example application for Docker & Kubernetes


## Applications

Directory | Application
----------|-----------------------------
app_v1    | The simplest Docker application
app_v2    | Simple application with some tuning (better build, `.dockerignore`)
app_v3    | App with redis deployed by docker-compose
app_v4    | App with redis deployed in Kubernetes

## Hints

Build application with command (execute in directory with `Dockerfile`):

`docker build -t name_of_your_app .`
