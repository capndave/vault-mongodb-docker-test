# vault-mongodb-docker-test

Playground to test secret management with hashicorp vault and mongodb

## Setup

1. Install docker and docker-compose. Instructions [here](https://docs.docker.com/engine/install/)
2. Pull docker images for vault and mongodb with `docker pull vault` and `docker pull mongodb`
3. Set up a volume to save mongodb data to (which will be saved to your computer even if the mongo docker container closes), with `docker volume create mongo_data`