FROM node:16.15.1
# ARG TAG=latest
# FROM node:$TAG
WORKDIR /app
COPY package*.json ./
RUN npm install
COPY . .
EXPOSE 8080
CMD ["node", "server.js"]
