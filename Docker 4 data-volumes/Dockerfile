FROM node:14

WORKDIR /app

COPY package.json .

RUN npm i

COPY . .

EXPOSE 80

VOLUME [ "/app/feedback" ]

CMD [ "node","server.js" ]

# 0  npm i
# Install Node.js dependencies from package.json.

# 1  node server.js
# Run Node.js app locally (outside Docker).

# 2  docker build -t feedback-node .
# Build Docker image with tag "feedback-node".

# 3  docker images -a
# List all Docker images.

# 4  docker run -d -p 3000:80 --name feedback-app --rm feedback-node
# Run container:
# -d → detached
# -p 3000:80 → map host 3000 to container 80
# --name → container name
# --rm → auto-remove when stopped

# 5  docker logs feedback-app
# View container logs.

# 6  docker stop feedback-app
# Stop container (auto-removed because of --rm).

# 7  docker image prune -a
# Remove all unused images.

# 8  docker images -a
# Verify remaining images.

# 9  docker build -t feedback-node .
# Rebuild image.

# 10 docker run -p 3000:80 --name feedback-app --rm feedback-node
# Run container in foreground mode (no -d).

# 11 docker stop feedback-app
# Stop container.

# 12 docker run -d -p 3000:80 --name feedback-app feedback-node
# Run container WITHOUT --rm (persistent container).

# 13 docker stop feedback-app
# Stop container (not deleted this time).

# 14 docker start feedback-app
# Restart existing stopped container.

# 15 docker stop feedback-app
# Stop container again.

# 16 docker images -a
# List all images.

# 17 docker image prune -a
# Remove all unused images.

# 18 docker build -t feedback-node:volumes .
# Build image with volumes variant.

# 19 docker run -d -p 3000:80 --name feedback-app --rm feedback-node:volumes
# Run container.

# 20 docker logs feedback-app
# View logs.

# 21 docker stop feedback-app
# Stop container.

# 22 docker image prune
# Remove dangling images.

# 23 docker build -t feedback-node:volumes .
# Rebuild volumes image.

# 24 docker run -d -p 3000:80 --name feedback-app --rm feedback-node:volumes
# Run container.

# 25 docker logs feedback-app
# View logs.

# 26 docker image prune
# Cleanup dangling images.

# 27 docker build -t feedback-node:volumes .
# Rebuild again.

# 28 docker run -d -p 3000:80 --name feedback-app --rm feedback-node:volumes
# Run container.

# 29 docker container prune
# Remove all stopped containers.

# 30 docker run -d -p 3000:80 --name feedback-app --rm feedback-node:volumes
# Run container again.

# 31 docker stop feedback-app
# Stop container.

# 32 docker ps
# Show running containers.

# 33 docker run -d -p 3000:80 --name feedback-app --rm feedback-node:volumes
# Run container again.

# 34 docker stop feedback-app
# Stop container.

# 35 docker run -d -p 3000:80 --name feedback-app --rm feedback-node:volumes
# Run container again.