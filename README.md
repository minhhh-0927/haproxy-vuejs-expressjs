# Example LB system with Vuejs and Expressjs

# Configuration
- Check you ip local. Then, push IP to `haproxy/haproxy.cfg` config file.

```buildoutcfg
server vue-ui1 <IP>:8001 check
server vue-ui2 <IP>:8002 check
```

# Build
```sh
docker-compose build
docker-compose up -d
docker-compise logs -f
```

# Source
- https://viblo.asia/p/loadbalancing-webserver-don-gian-voi-haproxy-tren-ubuntu-server-NbmvbAzlkYO
- https://github.com/bbachi/vuejs-nodejs-docker-compose


