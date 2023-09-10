Nginx proxy with docker-compose

See https://hub.docker.com/r/nginxproxy/nginx-proxy 

### Usage

```bash
cp .env.example .env
docker network create proxy_nw
docker-compose up -d
```
