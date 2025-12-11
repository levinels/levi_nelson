# Start from Ubuntu-based dev container
FROM mcr.microsoft.com/devcontainers/base:ubuntu

# Install curl and build-essential for Node.js
RUN apt-get update && apt-get install -y curl build-essential python3-pip

# Install Node.js LTS (e.g., v16)
RUN curl -fsSL https://deb.nodesource.com/setup_16.x | bash - \
    && apt-get install -y nodejs

# Confirm versions
RUN node -v && npm -v && python3 --version && pip3 --version
