FROM python:3.12-bookworm
LABEL org.opencontainers.image.source=https://github.com/AmakoYoko/action-runners
RUN apt-get update && apt-get install -y --no-install-recommends git curl jq build-essential openssh-client rsync && rm -rf /var/lib/apt/lists/* && pip install --no-cache-dir uv
WORKDIR /work
