# kong-docker-compose-starter

Kong API management in portable way

# Includes

- [x] Kong API gateway
- [x] Konga: Kong Admin GUI
- [x] PostgreSQL: Kong storage
- [x] Static IP address for Kong network (CIDR)
- [x] Blocking Admin API port on docker host. It can connect via Konga only.
- [x] Run migration for Kong.
- [ ] Connected PostgreSQL or Cassandra outside.

Kong:
<https://konghq.com/kong>

Konga:
<https://github.com/pantsel/konga>

# How to use

1. Install Docker

   - <https://www.docker.com/products/docker-desktop>
   - <https://docs.docker.com/>
   - <https://docs.docker.com/install/>

2. Then, Start and stop via docker-compose up command
   - Start
     > docker-compose up -d
   - Stop
     > docker-compose down

# Author

### Thanaphoom Babparn
