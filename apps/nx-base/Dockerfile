# https://medium.com/swlh/nx-nestjs-react-docker-deploys-928a55fc19fd
FROM node:lts-bullseye-slim as builder
ARG NODE_ENV
ARG BUILD_FLAG
WORKDIR /repo
COPY ../../ .
RUN yarn install
