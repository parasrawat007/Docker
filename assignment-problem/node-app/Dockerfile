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
# List all containers.

# 3  docker stop sad_swanson
# Stop container.

# 4  docker images -a
# List all images.

# 5  docker build .
# Build image again.

# 6  docker run -p 3000:3000 --name NodeJsApp 6732693c77fbd9b6b2ae2c787e62735a4c4653611dc5c1dd6e92a917a2f59119
# Run container with name.

# 7  docker ps -a
# List containers.

# 8  docker stop NodeJsApp
# Stop container.

# 9  docker start -a NodeJsApp
# Start and attach container.

# 10 docker stop NodeJsApp
# Stop container again.

# 11 docker ps -a
# Verify container state.

# 12 docker rm NodeJsApp charming_nightingale
# Remove containers.

# 13 docker ps -a
# Confirm removal.

# 14 docker images -a
# List images.

# 15 docker image prune -a
# Remove unused images.

# 16 docker build -t nodejsapp:latest .
# Build and tag image.

# 17 docker run -p 3000:3000 -d --rm --name NodeJsApp nodejsapp:latest
# Run container in detached mode with auto-removal.

# 18 docker ps -a
# List containers.

# 19 docker images -a
# List images.

# 20 docker stop NodeJsApp
# Stop container (auto-removed due to --rm).

# 21 docker ps -a
# Confirm container removal.

# 22 docker tag nodejsapp:latest parasrawat007/node-hello-world:latest
# Tag local image for Docker Hub (username/repo:tag).

# 23 docker images
# Verify tagged image.

# 24 docker rmi parasrawat007/node-hello-world:latest
# Remove tagged image.

# 25 docker images -a
# Verify image removal.

# 26 docker tag nodejsapp:latest parasrawat007/node-hello-world:latest
# Recreate tag.

# 27 docker images -a
# Confirm tag exists.

# 28 docker login
# Authenticate with Docker Hub.

# 29 docker push parasrawat007/node-hello-world:latest
# Push image to Docker Hub repository.