
# Start from a clean Python image
FROM python:3.10-slim

LABEL org.opencontainers.image.source https://github.com/scleestacks/scleestacks
LABEL maintainer="Chris Tastad <christopher.tastad@mssm.edu>"

# Set the working directory in the container
WORKDIR /app

# Install biolord
RUN pip install --no-cache-dir biolord==0.0.3

