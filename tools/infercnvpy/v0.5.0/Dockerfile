
# Start from a clean Python image
FROM python:3.10-slim

LABEL org.opencontainers.image.source https://github.com/scleestacks/scleestacks
LABEL maintainer="Chris Tastad <christopher.tastad@mssm.edu>"

# Set the working directory in the container
WORKDIR /app

# Install infercnvpy
RUN pip install --no-cache-dir infercnvpy==0.5.0

# Test
# >>> import infercnvpy as cnv
# adata = cnv.datasets.maynard2020_3k()
