# Common Compose Services

## Description
This repository contains common compose services for development with docker compose.

Using volumes for data storage is recommended.

## Usage
```bash
docker compose -f docker-compose-v2.yml up -d
```

## Services

- postgresdb
- mongodb
- redisdb
- rabbitmq

## Volumes
- postgres_data
- redis_data
- mongodb_data
- rabbitmq_data

## Networks
- shared-network