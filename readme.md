# Github actions example of docker image build and push
This repository contains an example of how to build a docker image, upload it to docker, and leverage the docker actions to add labels and tags based on git meta-info.

## Requirements
* Github account with Github Actions Enabled
* Dockerhub account

## Usage of the example
* Fork this repositorio onto your Github account
* Clone the code and adjust the config with you dockerhub account / Dockerfile
* Create a PAT in Dockerhub to identify yourseld with the appropriate permissions
* Add the needed secrets in Github: DOCKERHUB_USERNAME, DOCKERHUB_TOKEN
* The action triggers pushing a tag with the followinf format: `v*.*.*`