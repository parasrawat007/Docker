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


# ------------------------------------------------
    # 0  docker ps -a
# List all containers (running + stopped).

# 1  docker rm hardcore_feistel crazy_noyce lucid_bose lucid_bose hungry_bell goofy_mclean magical_swartz hopeful_leavitt trusting_herschel vibrant_payne naughty_khorana friendly_jackson quirky_franklin elated_shirley ...
# Remove multiple stopped containers by name.
# (Containers must be stopped before removal.)

# 2  cls
# Clear terminal screen (Windows command, not Docker).

# 3  docker ps -a
# Verify remaining containers after deletion.

# 4  docker rm awesome_jemison
# Remove specific stopped container.

# 5  docker ps -a
# Confirm container removal.

# 6  cls
# Clear terminal screen.

# 7  docker images
# List all Docker images stored locally.

# 8  docker rmi 39f92e620aa3
# Remove image by image ID.
# (Fails if image is used by any container.)

# 9  docker image prune
# Remove dangling (unused) images.

# 10 cd '.\Docker 2\'
# Change directory to project folder.

# 11 docker images
# List images again.

# 12 docker images i
# Invalid usage — "docker images" does not take arbitrary arguments like "i".

# 13 docker images u
# Invalid usage — same issue as above.

# 14 cls
# Clear terminal.

# 15 docker build
# Invalid — missing build context (like ".").

# 16 docker build .0
# Invalid — incorrect build context path.

# 17 docker build .
# Correct — build image from current directory.

# 18 docker images
# Verify new image was created.

# 19 docker run 2c9c916b75d1f669aff2058705f09ad3506348718931728f57f7fd98307732e8
# Create and start container from image ID (no port mapping).

# 20 docker run -p 8000:80 2c9c916b75d1f669aff2058705f09ad3506348718931728f57f7fd98307732e8
# Run container and map host port 8000 → container port 80.

# 21 docker images
# List images again (no change expected).

# 22 docker stop 2c9c916b75d1f669aff2058705f09ad3506348718931728f57f7fd98307732e8
# Incorrect usage — stop expects container ID, not image ID.

# 23 docker ps
# Show running containers.

# 24 docker stop eloquent_goldstine
# Stop container by name.

# 25 docker stop nervous_panini
# Stop another container.

# 26 docker images
# List images.

# 27 docker images -a
# Show all images (including intermediate layers).

# 28 docker ps -a
# List all containers.

# 29 docker stop nervous_paini
# Likely typo — container name incorrect.

# 30 docker stop nervous_panini
# Stop correct container.

# 31 docker stop eloquent_goldstine
# Stop container again (if still running).

# 32 docker run -p 3000:80 -d --rm 2c9c916b75d1f669aff2058705f09ad3506348718931728f57f7fd98307732e8
# Run container in detached mode:
# -p 3000:80 → port mapping
# -d → run in background
# --rm → automatically remove container when stopped

# 33 docker ps -a
# List containers (this one will disappear after stop because of --rm).

# 34 docker stop tender_lewin
# Stop running container.

# 35 docker ps -a
# Confirm container removal (if --rm was used).

# -----------------------------------------------------------------------'
# 0  docker images -a
# List all images including intermediate (dangling) layers.
# Useful to inspect full image history after multiple builds.

# 1  docker inspect 2c9c916b75d1
# Display detailed low-level JSON metadata about the image or container.
# If this ID belongs to:
#   - an image → shows image config, layers, environment variables, entrypoint, etc.
#   - a container → shows runtime details (IP, mounts, ports, state, etc.)

# -----------------------------------------------------------------------------
# 0  docker ps -a
# List all containers (running + stopped).

# 1  docker cp Dummy/. nervous_panini:/test
# Copy everything inside local folder "Dummy" into the container
# named "nervous_panini" at path /test.
# Format: docker cp <local_path> <container_name>:<container_path>

# 2  docker cp nervous_panini:/test Dummy
# Copy the entire /test directory from the container
# to the local folder "Dummy".
# Format: docker cp <container_name>:<container_path> <local_path>

# 3  docker cp nervous_panini:/test/Test.txt Dummy
# Copy a specific file (Test.txt) from container path /test
# to local folder "Dummy".

# --------------------------------------------------------------------------------
    # 0  docker images -a
# List all images, including intermediate layers.

# 1  docker run -p 3000:80 -d --rm --name goalsapp 2c9c916b75d1
# Run container from image ID:
# -p 3000:80 → map host 3000 to container 80
# -d → detached mode
# --rm → auto-remove container when stopped
# --name goalsapp → assign container name

# 2  docker stop goalsapp
# Stop the container.
# Because --rm was used, container is automatically deleted after stop.

# 3  docker ps -a
# List all containers (goalsapp will not appear due to --rm).

# 4  docker build -t goalsapp:latest .
# Build image and tag it properly.
# goalsapp = repository name
# latest = tag

# 5  docker images -a
# Verify new tagged image exists.

# 6  docker run -p 3000:80 -d --rm --name goalsapp goalsapp:latest
# Run container using tagged image (professional practice).

# 7  docker stop goalsapp
# Stop container (auto-removed again because of --rm).

# 8  docker prune -a
# Invalid — prune is a subcommand (needs object type).

# 9  docker prune --a
# Invalid — same issue.

# 10 docker prune -a
# Invalid again.

# 11 docker images prune -a
# Invalid syntax — wrong command order.

# 12 docker images -a
# List images (no change from invalid commands).

# 13 docker image prune -a
# Correct — remove all unused images (not referenced by containers).

# 14 docker images -a
# Verify unused images were removed.

# 15 docker ps -a
# List containers.

# 16 docker ps -a
# Same command repeated.

# 17 docker rm nervous_panini eloquent_goldstine
# Remove specific stopped containers.

# 18 docker image prune -a
# Remove all unused images again (cleanup).

# 19 docker images -a
# Final verification of remaining images.