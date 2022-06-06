

# Deployment


## Deploy
docker-compose up -d


## Build and push
docker login

docker buildx build \
    --platform linux/amd64,linux/arm64 \
    -t altayatalay/web:latest \
    --push .