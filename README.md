> Note: The server was up and running in the Github Code Spaces, so take advantage of it for testing

# ELK Stack

```
docker compose -f docker-compose.yml -f extensions/filebeat/filebeat-compose.yml -f extensions/apm-server/apm-server-compose.yml up -d
```

The above command will spin up

- Elastic Search
- Kibana
- Filebeat
- APM Server

# Hasura

```
cd hasura
docker compose up -d
```
