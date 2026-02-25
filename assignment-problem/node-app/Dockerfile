FROM node

WORKDIR /app

COPY package.json /app/

RUN npm i

COPY . /app/

EXPOSE 3000

CMD ["node","server.js"]

# 0  docker build .
# Build image from Dockerfile in current directory.

# 1  docker run -p 3000:3000 17438b1d0d9a4c9d6aa0a3b7e1f602de612836712c817adab2ceb4ae54f875ae
# Run container from image ID with port mapping.

# 2  docker ps -a
# List all containers (running + stopped).

# 3  docker stop sad_swanson
# Stop container created from previous run.

# 4  docker images -a
# List all local images including intermediate layers.

# 5  docker build .
# Build image again (untagged).

# 6  docker run -p 3000:3000 --name NodeJsApp 6732693c77fbd9b6b2ae2c787e62735a4c4653611dc5c1dd6e92a917a2f59119
# Run container from image ID and assign name NodeJsApp.

# 7  docker ps -a
# List all containers.

# 8  docker stop NodeJsApp
# Gracefully stop container.

# 9  docker start -a NodeJsApp
# Restart container and attach to output.

# 10 docker stop NodeJsApp
# Stop container again.

# 11 docker ps -a
# Verify container state.

# 12 docker rm NodeJsApp charming_nightingale
# Remove stopped containers.

# 13 docker ps -a
# Confirm containers removed.

# 14 docker images -a
# List all images.

# 15 docker image prune -a
# Remove all unused images.

# 16 docker build -t nodejsapp:latest .
# Build image and tag properly.

# 17 docker run -p 3000:3000 -d --rm --name NodeJsApp nodejsapp:latest
# Run container in detached mode with auto-removal.

# 18 docker ps -a
# List containers.

# 19 docker images -a
# List images.

# 20 docker stop NodeJsApp
# Stop container.
# It is auto-removed because --rm was used.

# 21 docker ps -a
# Confirm container no longer exists.