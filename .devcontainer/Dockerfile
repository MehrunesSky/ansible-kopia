FROM thegeeklab/ansible-dev-tools

ENV DOCKER_HOST=unix:///var/run/user/1000/docker.sock


# Installer les dépendances et le client Docker
RUN apk update && apk add --no-cache \
    docker-cli \
    curl \
    bash \
    rsync
