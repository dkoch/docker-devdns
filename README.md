# devdns
An alpine-based, dockerized version of Robbie Vanbrabant's
[devdns](https://github.com/robbiev/devdns).

# Usage
```
docker run -d --name devdns -p 5300:5300/udp --restart always dkoch/devdns
```
