FROM cyberbotics/webots:latest

RUN apt-get update && apt-get install -q -y --no-install-recommends \
    libeigen3-dev \
    libopencv-dev \
    && rm -rf /var/lib/apt/lists/*
WORKDIR /root