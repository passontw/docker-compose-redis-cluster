# How to create local redis cluster

> `en0` is your network interface that you're using right now.

```bash
ip=$(ifconfig eth0 | grep "inet " | awk '{print $2}') docker-compose up -d --build
```
