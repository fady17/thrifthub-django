# Install Python
FROM mcr.microsoft.com/vscode/devcontainers/python:3.9

# Install Node.js
RUN curl -fsSL https://deb.nodesource.com/setup_14.x | bash -
RUN apt-get install -y nodejs

# Set the working directory
WORKDIR /workspace
