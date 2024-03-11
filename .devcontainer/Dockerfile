FROM oven/bun:debian

# Config Bun
ENV PATH="~/.bun/bin:${PATH}"
ENV GIT_AUTHOR_NAME="shiho"
ENV GIT_AUTHOR_EMAIL="aphrodite.shiho@icloud.com"

RUN ln -s /usr/local/bin/bun /usr/local/bin/node

# Update packages
RUN apt-get update

# Install Git
RUN apt-get update && apt-get install -y git
