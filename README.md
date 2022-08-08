# docker-images

These are docker images from other projects, when either no docker images exist or they do not suit my needs.

## PlantUML

A docker image around the plantUML CLI, so I can use it without local installation (or Java for that matter)
For more information see https://plantuml.com

To use like the local command set the following alias:

```
alias plantuml="docker run -it --rm ghcr.io/cypherfox/docker-images/plantuml-cli:0.0.0-355dbb9"
```
