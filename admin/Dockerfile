# syntax=docker/dockerfile:1

FROM node:18-alpine
WORKDIR /app
COPY ./admin/package.json .
RUN npm install
COPY ./admin .
CMD ["npm", "run", "dev"]
EXPOSE 8080