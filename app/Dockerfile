FROM node:19.6

WORKDIR /app

COPY package*.json ./
RUN npm install
COPY .. ./
CMD node index.js
