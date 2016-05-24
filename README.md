# docker-wavefront-forwarder-builder

This builds the wavefront-push-agent.jar and exports it to /dist

# Usage

```
docker run -it --rm -v ~/:/dist -e VERSION=3.14 mvisonneau/wavefront-forwarder-builder:latest
```
