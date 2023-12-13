# Docker
# My Website

This is a simple website hosted in a Docker container using Nginx.

## Build and Run Instructions

### Prerequisites

- Docker installed on your machine.

### Build the Docker Container

Run the following command to build the Docker container:

```bash
docker build -t my-container .
docker run -p 8090:80 my-container
