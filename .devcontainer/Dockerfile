# Use the correct base image
FROM mcr.microsoft.com/devcontainers/universal:2

# Install Node.js (latest LTS, required for Vue.js)
RUN curl -fsSL https://deb.nodesource.com/setup_18.x | bash - \
    && apt-get install -y nodejs

# Install Vue CLI globally
RUN npm install -g @vue/cli

# Install Flask
RUN pip3 install flask
