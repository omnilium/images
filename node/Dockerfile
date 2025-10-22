FROM node:22

LABEL maintainer="contact@omnilium.com"
LABEL description="Build image for NodeJS applications. Includes PNPM."

RUN npm install --global corepack@latest
RUN corepack enable pnpm
RUN corepack use pnpm@latest-10

ENTRYPOINT [ "bash" ]
