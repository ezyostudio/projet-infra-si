# 01-Station

```sh
docker-compose up

docker-compose exec tailscale tailscale up
# OR if you have an auth key
docker-compose exec tailscale tailscale up --authkey=$KEY
```

On can now access to the caddy server at http://station

### Configuration files
#### `Caddyfile`
