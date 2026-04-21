FROM node:14

WORKDIR /app

COPY package.json .

RUN npm i

COPY . .

EXPOSE 80

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

# 5  docker stop feedback-app
# Stop container (auto-removed because of --rm).

# 6  docker image prune -a
# Remove all unused images.

# 7  docker images -a
# Verify remaining images.

# 8  docker build -t feedback-node .
# Rebuild image.

# 9  docker run -d -p 3000:80 --name feedback-app --rm feedback-node
# Run container again (auto-remove enabled).

# 10 docker stop feedback-app
# Stop container (removed automatically).

# 11 docker run -p 3000:80 --name feedback-app --rm feedback-node
# Run container in foreground mode (no -d).

# 12 docker stop feedback-app
# Stop container.

# 13 docker run -d -p 3000:80 --name feedback-app feedback-node
# Run container WITHOUT --rm (persistent container).

# 14 docker stop feedback-app
# Stop container (not deleted this time).

# 15 docker start feedback-app
# Restart existing stopped container.

# 16 docker stop feedback-app
# Stop container again.