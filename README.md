# Synapse Docker image for Lippesola
This image has additional Modules and settings, which are not available in the base image.

## List of changes against the base image

* Add [synapse-auto-accept-invite](https://github.com/matrix-org/synapse-auto-accept-invite)

## Version setting

The Version of the built Synapse version is defined on `.github/workflows/docker-build.yaml`. Inside the file you'll find the `env.IMAGE_TAG` yaml Entry. 

## Docker Pull

`docker pull ghcr.io/lippesola/synapse:v1.76.0`.
