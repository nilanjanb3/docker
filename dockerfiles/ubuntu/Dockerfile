# Use the official Ubuntu image as the base image
FROM ubuntu:latest

# Update the package repositories and install necessary packages
RUN apt-get update && \
    apt-get install -y \
    neofetch \
    python3 \
    python3-pip \
    python-is-python3 \
    golang \
    nodejs \
    npm \
    terraform \
    docker.io \
    apt-transport-https \
    ca-certificates \
    curl \
    git \
    wget \
    vim \
    openjdk-11-jdk \
    openssh-server \
    && npm install -g n && n latest \
    && curl -sSL https://get.docker.com/ | sh \
    && curl -sSL https://packages.cloud.google.com/apt/doc/apt-key.gpg | apt-key add - \
    && add-apt-repository "deb https://apt.kubernetes.io/ kubernetes-xenial main" \
    && apt-get update && apt-get install -y kubectl \
    && apt-get clean \
    && rm -rf /var/lib/apt/lists/*

# Install Ansible using pip
RUN pip3 install ansible

# Set the working directory to /app
WORKDIR /app

# Expose SSH port for remote access
EXPOSE 22

# Define environment variables, if any
# ENV MY_ENV_VARIABLE=value

# Optionally, set a label for additional metadata
# LABEL version="1.0" description="My Development Environment"

# You can add more instructions based on your application requirements
CMD [ "neofetch" ]
