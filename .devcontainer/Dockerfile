# Use the correct base image
FROM mcr.microsoft.com/devcontainers/universal:2

# Install Node.js 16 (compatible with Vue CLI)
RUN curl -fsSL https://deb.nodesource.com/setup_16.x | bash - \
    && apt-get install -y nodejs

# Install Vue CLI
RUN npm install -g @vue/cli

# Install Flask
RUN pip3 install flask
