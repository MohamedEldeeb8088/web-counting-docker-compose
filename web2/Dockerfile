FROM node:19.5.0-alpine

WORKDIR /usr/src/app

COPY ./server.js ./
COPY ./package.json ./
RUN npm install


CMD ["npm","start"]