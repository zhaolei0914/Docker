# About
Kafka image adopted for Kubernetes Stateful pods
based on https://github.com/wurstmeister/kafka-docker.
I did a little clean-up and adopted for my needs.
# Build command
```
docker buildx build \
 --platform linux/arm64,linux/amd64 \
 --tag sergeykulagin/kafka:2.5.0 \
 --push .
```