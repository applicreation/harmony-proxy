# harmony-proxy

## Details

This is intended for local use only to replicate a simple load balancer.

## Usage

```yaml
---

services:
  proxy:
    image: ghcr.io/applicreation/harmony-proxy:latest
    ports:
      - 80:80
  # core and module config
```
