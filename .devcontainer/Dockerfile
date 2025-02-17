# .devcontainer/Dockerfile
FROM mcr.microsoft.com/devcontainers/universal

# Remove any pre-installed Hugo so the feature's install script can run
RUN apt-get update && apt-get remove -y hugo && rm -f /usr/local/hugo/bin/hugo && rm -rf /var/lib/apt/lists/*
