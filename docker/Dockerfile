# Script Name: Dockerfile (pgvector lab)
# Author: Amr
# Date of Creation: 2025-09-25
# Description: Custom PostgreSQL image with pgvector extension for vector DB testing.

FROM postgres:16

# Install pgvector extension
RUN apt-get update && \
    apt-get install -y postgresql-16-pgvector && \
    rm -rf /var/lib/apt/lists/*

# Expose Postgres port
EXPOSE 5432
