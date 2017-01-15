## Websockify on Docker for ARM

Docker Image for Websockify WebSocket to TCP proxy/bridge on ARM: https://hub.docker.com/r/mraerino/websockify-armhf/

For more information on Websockify, see the official project page: https://github.com/kanaka/websockify/

### Example
```shell
# Expose local port 5900 through WebSocket on port 8080
docker run --net=host -u nobody mraerino/websockify-arm 8080 localhost:5900
```
