# ColdFusion Developer Edition

## Tags
**latest**: 8.0.1

## Run
```sh
docker run -d -p 8500:8500 fabiohbarbosa/coldfusion
```

## Docker Compose
```yaml
coldfusion:
  container_name: coldfusion
  image: fabiohbarbosa/coldfusion
  ports:
  - "8500:8500"
```

## Access
http://localhost:8500/CFIDE/administrator/index.cfm

**User**: admin

**Password**: admin
