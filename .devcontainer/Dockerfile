FROM mcr.microsoft.com/devcontainers/base:ubuntu
# Install the xz-utils package
RUN apt-get update 

# Install Node.js (required for Vue)
RUN sudo apt-get update && \
    sudo apt-get install -y nodejs npm && \
    sudo npm install -g @vue/cli

# Install Python dependencies for Flask
RUN pip3 install flask