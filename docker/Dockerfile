# FROM ghcr.io/home-assistant/amd64-base-python:3.11-alpine3.17
FROM python:3-alpine
RUN apk add --no-cache nano
RUN python -m venv venv && \
    source venv/bin/activate && \
    pip install linode-cli
COPY rootfs /
