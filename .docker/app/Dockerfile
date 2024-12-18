FROM node:22-alpine as builder
WORKDIR /app
COPY /frontend .
RUN npm install --force
RUN npm run build
