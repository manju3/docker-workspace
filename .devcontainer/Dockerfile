FROM ubuntu:latest

# Install dependencies
RUN apt-get update && \
    apt-get -y install curl python3 python3-pip

# Install Node.js
RUN curl -sL https://deb.nodesource.com/setup_14.x | bash -
RUN apt-get install -y nodejs
RUN apt-get install -y git

# Set the working directory
# WORKDIR /app

# Expose the port that the application listens on
EXPOSE 3000