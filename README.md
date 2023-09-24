# Redis Cluster with Docker Compose

This project provides a Docker Compose configuration for creating a Redis cluster with 3 shards, each consisting of 2 replicas. 

## Prerequisites

Make sure you have Docker and Docker Compose installed on your system.

## Usage

1. Clone this repository to your local machine:

```bash
git clone https://github.com/erfanshekari/redis-cluster-docker-stack.git
cd redis-cluster-docker-stack
```

2. Set password for redis nodes to environment variables

```bash
export REDIS_PASSWORD=strong-password
```

3. Start the Redis cluster:

```bash
docker compose up -d
```

## Customization
Edit the compose.yml file to change the configuration and make additional customizations

## License
This project is licensed under the [MIT License](LICENSE.md).
