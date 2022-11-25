# Releasing

## Docker image

1. Login to Docker Hub
   ```bash
   docker login
   ```
2. Build & push images
   ```bash
   mvn clean install -Ddocker.image.tag=<TAG_NAME> -Ddocker.skip=false -Ddocker.skip.push=false
   ```