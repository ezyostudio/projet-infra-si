# 02-metabase

```sh
docker-compose up

docker-compose exec radarr sh -c /scripts/radarr_init.sh
docker-compose restart radarr


docker-compose exec sonarr sh -c /scripts/sonarr_init.sh
docker-compose restart sonarr
```

On can now access to the caddy server at http://station

### Configuration files
#### `Caddyfile`
