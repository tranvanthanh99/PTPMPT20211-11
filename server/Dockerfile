FROM node:lts-alpine as base
WORKDIR /server
COPY package*.json ./
RUN npm install
COPY ./ ./
RUN npm run build
EXPOSE 3333