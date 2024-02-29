# Use the latest Ubuntu image as the base
FROM ubuntu:latest

# Update APT and upgrade installed packages
RUN apt-get update && apt-get upgrade -y

# Install 'echo' command
RUN apt-get install -y coreutils

# Install python3, python3-pip, and flask
RUN apt-get install -y python3 python3-pip
RUN pip install flask

# Set working directory
WORKDIR /app

# Copy api.py to Docker image
COPY ./api.py /app/api.py

# Command to run when container starts
CMD [ "echo", "Hello, World!" ]