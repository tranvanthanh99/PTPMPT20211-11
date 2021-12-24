FROM node:lts-alpine as base
WORKDIR /app
COPY ./ ./
RUN npm install && npm run build
EXPOSE 3000