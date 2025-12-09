
FROM rust:1.91.1-bookworm

RUN apt-get update \
    && apt-get install -y --no-install-recommends vim git curl \
    && rm -rf /var/lib/apt/lists/*

WORKDIR /var/www/html

RUN mkdir -p log/src

COPY 20251209.txt /var/www/html/log/src/
