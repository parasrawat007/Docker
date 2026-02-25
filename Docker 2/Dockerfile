FROM node

WORKDIR /app

COPY package.json /app

RUN npm i

COPY . /app

EXPOSE 80

CMD [ "node" ,"server.js" ]

# 0  docker build .
# Build an image from the Dockerfile in the current directory.

# 1  docker run 069b3f2acad5264f6270cc15c4bcf898fbc858298d19c5f8b20455bdf4c7d634
# Create and start a new container from the given image ID (no port mapping).

# 2  docker ps
# List currently running containers.

# 3  docker stop amazing_snyder
# Gracefully stop the running container named "amazing_snyder".

# 4  docker ps
# Verify running containers after stopping.

# 5  docker ps -a
# List all containers (running + stopped).

# 6  docker run -p 3000:80 069b3f2acad5264f6270cc15c4bcf898fbc858298d19c5f8b20455bdf4c7d634
# Run a new container and map host port 3000 → container port 80.

# 7  docker ps
# Check running containers.

# 8  docker stop competent_tharp
# Stop container named "competent_tharp".

# 9  docker build
# Attempt to build (incorrect — missing context like ".").

# 10 docker build .
# Correct build command using current directory.

# 11 docker run -p 3000:80 a0859ac0e516966bf5e44dfc14fe26f46da1d6bcaf470fd050d7daf4ce055d39
# Run container from new image with port mapping.

# 12 docker run -p 3000:80 a0859ac0e516966bf5e44dfc14fe26f46da1d6bcaf470fd050d7daf4ce055d39
# Attempt to run again (likely fails if port already in use).

# 13 docker stop a0859ac0e516966bf5e44dfc14fe26f46da1d6bcaf470fd050d7daf4ce055d39
# Incorrect usage — stop expects container ID, not image ID.

# 14 docker run -p 3000:80 a0859ac0e516966bf5e44dfc14fe26f46da1d6bcaf470fd050d7daf4ce055d39
# Run container again from same image.

# 15 docker -ps
# Invalid command (typo — should be docker ps).

# 16 docker ps
# List running containers.

# 17 docker stop elated_shirley
# Stop container by name.

# 18 docker run -p 3000:80 a0859ac0e516966bf5e44dfc14fe26f46da1d6bcaf470fd050d7daf4ce055d39
# Run new container again.

# 19 docker ps
# Verify running containers.

# 20 docker stop naughty_khorana
# Stop container.

# 21 docker build .
# Rebuild image (new image ID generated).

# 22 docker run -p 3000:80 b57c8ddce4b3a53d6c472c431a4370d13cb20edaca4598305629db5a35ce0ec7
# Run container from new image.

# 23 docker ps
# Check running containers.

# 24 docker stop vibrant_payne
# Stop container.

# 25 docker build .
# Rebuild image again.

# 26 docker run -p 3000:80 68b137d054ba12c55fbbf5959f156100967b546c4c619ba582d8eb1ea4d637a
# Run container from rebuilt image.

# 27 docker ps
# List running containers.

# 28 docker stop trusting_herschel
# Stop container.

# 29 docker build .
# Rebuild image.

# 30 docker run -p 3000:80 b5c9c7cc54a76ffa404904a0306ab0fc071d77e040f8b4cb9d120b0e97e031b3
# Run container from latest image.

# 31 docker build .
# Rebuild image again.

# 32 docker run -p 3000:80 75d7bbbe71fc1ab68bd5c6ccc782df90aa2a4a5a33129af257b38da89160eda4
# Run container from image.

# 33 docker ps
# List running containers.

# 34 docker kill hopeful_leavitt
# Force stop container immediately (SIGKILL).

# 35 docker run -p 3000:80 75d7bbbe71fc1ab68bd5c6ccc782df90aa2a4a5a33129af257b38da89160eda4
# Run container again.

# 36 docker ps -a
# Show all containers.

# 37 docker ps -a
# Same as above (duplicate).

# 38 docker start magical_swartz
# Start an existing stopped container.

# 39 docker stop magical_swartz
# Stop container.

# 40 docker start magical_swartz
# Restart stopped container.

# 41 docker run -p 8000:80 75d7bbbe71fc
# Run new container mapping host port 8000.

# 42 docker start magical_swartz
# Start container again.

# 43 docker ps
# List running containers.

# 44 docker stop goofy_mclean
# Stop container.

# 45 docker run -p 8000:80 -d 75d7bbbe71fc
# Run container in detached mode (-d).

# 46 docker run attack e770cdcd24dfe57a68b35dee786bb1347b2edc112976da9d8386ea0667cbe98a
# Invalid command ("attack" is not a docker run option).

# 47 docker ps
# List running containers.

# 48 docker attach hungry_bell
# Attach terminal to running container.

# 49 docker stop hungry_bell
# Stop container.

# 50 docker stop magical_swartz
# Stop container.

# 51 docker run magical_swartz
# Incorrect — docker run expects image, not container name.

# 52 docker run magical_swartz
# Same mistake as above.

# 53 docker ps -a
# Show all containers.

# 54 docker start goofy_mclean
# Start existing container.

# 55 docker logs goofy_mclean
# Show container logs.

# 56 docker logs -f goofy_mclean
# Stream logs in real time.

# 57 docker stop goofy_mclean
# Stop container.