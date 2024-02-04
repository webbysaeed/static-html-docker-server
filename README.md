# Dockerized Static HTML Server

This repository contains a Dockerfile to create a lightweight web server serving a static HTML page using Nginx.

## Getting Started

Follow these instructions to set up and run the Dockerized static HTML server on your local machine.

### Prerequisites

- [Docker](https://www.docker.com/)

### Building the Docker Image

Build the Docker image using the provided Dockerfile.

```bash
docker build -t static-html-server .

Running the Docker Container

Run a Docker container based on the created image.
docker run -p 8080:80 static-html-server

Visit http://localhost:8080 in your web browser to view the static HTML content.



