FROM node:16.13.1-alpine as build-stage
WORKDIR /app
COPY . .
RUN yarn install
CMD yarn serve