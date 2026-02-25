FROM python

WORKDIR /app

COPY . /app

CMD [ "python","rng.py" ]

# 0  docker build .
# Build an image from the Dockerfile in the current directory.

# 1  docker run
# Invalid usage — docker run requires an image name or ID.

# 2  docker run f5088007dd6ec8af8c3ee29b6977723140d6ad23252901c3d7c9d5a74cb57b96
# Create and start a new container from the specified image ID.

# 3  docker run it f5088007dd6ec8af8c3ee29b6977723140d6ad23252901c3d7c9d5a74cb57b96
# Invalid syntax — "it" must be written as "-it".

# 4  docker run -it f5088007dd6ec8af8c3ee29b6977723140d6ad23252901c3d7c9d5a74cb57b96
# Correct — run container interactively with terminal attached.
# -i = keep STDIN open
# -t = allocate pseudo-terminal

# 5  docker ps -a
# List all containers (running + stopped).

# 6  docker start hardcore_feistel
# Start an existing stopped container named "hardcore_feistel".

# 7  docker ps
# Show currently running containers.

# 8  docker stop hardcore_feistel
# Gracefully stop the container.

# 9  docker run -a hardcore_feistel
# Invalid — docker run expects an image, not a container name.
# -a requires specifying a stream (stdin|stdout|stderr).

# 10 docker start -a hardcore_feistel
# Start container and attach to its output streams.

# 11 docker stop hardcore_feistel
# Stop container again.

# 12 docker start -i hardcore_feistel
# Start container and attach interactively (keeps STDIN open).