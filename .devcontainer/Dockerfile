FROM mcr.microsoft.com/devcontainers/python:3.12

RUN apt-get update && apt-get install -y \
    postgresql-client \
    sqlite3 \
    git-lfs \
    curl \
    wget \
    && rm -rf /var/lib/apt/lists/*