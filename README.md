# Demo of an API-first Workflow For Developing and Testing gRPC Microservices

This example assumes the teams are working in a monorepo. Other approaches are equally valid.

## How to use this sample monorepo to test API-first workflow with Traffic Parrot

1. Fork this repository.
2. Define GitHub Actions Secrets by opening You repo "Settings" -> Secrets ->  Actions
* DOCKER_REGISTRY_HOST - hostname for the DOcker registry (i.e. you can use free a JFrog plan)
* DOCKER_REGISTRY_USER - username to yourt docker registry 
* DOCKER_REGISTRY_PASS - password for the Docker registry
* TP_FILE - HTTP URL of the Traffic Parrot ZIP file you got after filling in the form https://trafficparrot.com/trial.html

## Benefits of API-first apporach

For details about why to use API-first apporach see our artcile on InfoQ https://www.infoq.com/articles/api-mocking-break-dependencies/
