FROM node:15-alpine

WORKDIR /usr/src/app


COPY package*.json ./
COPY server.js ./

RUN npm install


EXPOSE 8080
CMD [ "node", "server.js" ]
