# ngrok-nginx-docker

Want to expose your web server to a public URL via ngork but afraid of the security concerns of forwarding your port to ngrok? Secure the connection by encapsulating the ngrok process in a docker container! 

This repo is a way of containerizing a ngrok container that will route the ngrok URL to another nginx container. You can then configure nginx as a reverse proxy to route to other web services in the same docker network.

## Quick Start

```
docker-compose up
```

