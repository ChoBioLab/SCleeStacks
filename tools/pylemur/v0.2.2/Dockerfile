
# Start from a clean Python image
FROM python:3.10-slim

LABEL org.opencontainers.image.source https://github.com/scleestacks/scleestacks
LABEL maintainer="Chris Tastad <christopher.tastad@mssm.edu>"

# Set the working directory in the container
WORKDIR /app

# Install pyLemur
RUN pip install --no-cache-dir pyLemur==0.2.2

# Test
# >>> import pylemur
# >>> model = pylemur.tl.LEMUR(adata, design = "~ label", n_embedding=15)

