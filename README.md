# Bee11 Microservices Nest

Docker image for Nest CLI to use as build container.


![Docker stats](https://dockeri.co/image/naologic/bee11-microservices-dev-docker)


Currently this image uses node 12 (npm 6) and node:lts-slim as base distribution.

## Example usage 

To run the Nest CLI development server from docker you need to map the port.
For example use
```
cd MyDemo
docker run -p 33000-33050:33000-33050" -v "$PWD":/app naologic/bee11-microservices-dev-docker npm run start:dev
```
