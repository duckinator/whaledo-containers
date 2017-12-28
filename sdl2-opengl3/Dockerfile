FROM whaledo/sdl2

RUN apt-get update \
    && DEBIAN_FRONTEND=noninteractive apt-get install -y libglew-dev opengl-dev \
    && rm -rf /var/lib/apt/lists/*
