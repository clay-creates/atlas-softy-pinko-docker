# Use the latest Ubuntu image as the base
FROM ubuntu:latest

# Update APT and upgrade installed packages
RUN apt-get update && apt-get upgrade -y

# Install 'echo' command
RUN apt-get install -y coreutils

# Command to run when container starts
CMD [ "echo", "Hello, World!" ]