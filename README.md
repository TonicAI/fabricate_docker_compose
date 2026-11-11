# Tonic Fabricate Docker Compose

This repository contains the `docker-compose.yml` and `.template.env` templates for deploying Fabricate using Docker Compose.

The Fabricate installation requires access to the Tonic private Docker container registry.  
Reach out to support@tonic.ai to obtain your container registry login credentials.

Please see [CHANGELOG](CHANGELOG.md) and upgrade instructions before migrating existing instances.

## Instructions

1. Clone this repository:
    ```bash
    git clone git@github.com:TonicAI/fabricate_docker_compose.git
    cd fabricate_docker_compose
    ```
2. Rename the `.template.env` file to `.env`:
3. Follow the instructions in the [Self-hosting Fabricate using Docker Compose](https://docs.tonic.ai/fabricate/self-hosting-fabricate/deploying-and-managing-a-self-hosted-instance/using-docker-compose/completing-a-docker-compose-deployment) guide to complete the deployment.

## Prerequisites

- [Docker Engine](https://docs.docker.com/engine/install/)
- [Docker Compose](https://docs.docker.com/compose/install/)
- Login credentials for the Tonic private Docker container registry (Quay.io)

See [System Requirements](https://docs.tonic.ai/fabricate/self-hosting-fabricate/deploying-and-managing-a-self-hosted-instance/using-docker-compose/system-requirements-for-docker-compose-deployment) for more information about Docker Compose deployment requirements.