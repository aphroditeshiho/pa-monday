FROM oven/bun:debian

# Config Bun
ENV PATH="~/.bun/bin:${PATH}"

RUN ln -s /usr/local/bin/bun /usr/local/bin/node

# Update packages
RUN apt-get update
