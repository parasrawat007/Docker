FROM python

WORKDIR /app

COPY . /app/

CMD [ "python","bmi.py" ]
# 0  docker build .
# Build image from Dockerfile (untagged).

# 1  docker run -it f0c45ec96c3ce1592d581e984f283be97e0a3d5ecf08e94e3f834dceafcb9044
# Run container interactively from image ID.

# 2  docker ps -a
# List all containers.

# 3  docker images -a
# List all images.

# 4  docker rmi f0c45ec96c3c
# Remove image by ID (must not be used by any container).

# 5  docker build -t BMIApp:Latest .
# Build and tag image (capitalization allowed but not recommended).

# 6  docker build -t bmiapp:latest .
# Better practice: lowercase repository and tag.

# 7  docker run -it --name BMIApp bmiapp:latest
# Run container interactively and assign name BMIApp.

# 8  docker ps -a
# List all containers.

# 9  docker rm BMIApp
# Remove stopped container BMIApp.

# 10 docker ps -a
# Verify removal.

# 11 docker rm sad_swanson
# Remove another stopped container.

# 12 docker run -it --name BMIApp --rm bmiapp:latest
# Run container interactively.
# --rm → auto-remove when stopped.