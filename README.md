# Docker Symfony :whale:

Basic stack of containers for Symfony Application development.

## Installation

1. Create a `.env` file

    ```bash
    touch .env
    ```


2. Build/run containers with (with and without detached mode)

    ```bash
    docker-compose build
    docker-compose up -d
    ```

## Usage

Run `docker-compose up -d` and `docker-compose ps`

Nginx is now running at `localhost`