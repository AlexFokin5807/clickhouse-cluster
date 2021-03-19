# Clickhouse Cluster

Clickhouse cluster with 2 shards built with docker-compose.

## Run

```sh
make config up
```

Containers will be available in docker network `172.23.0.0/24`

| Container    | Address     |
| ------------ | ----------- |
| clickhouse01 | 172.23.0.11 |
| clickhouse02 | 172.23.0.12 |

## Profiles

- `default` - no password
- `admin` - password `123`

# 
