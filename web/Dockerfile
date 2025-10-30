FROM node:25-alpine3.21

WORKDIR /app

COPY package.josn package-lock.json ./
RUN npm ci

COPY ./server.js ./

CMD [ "npm" , "start" ]
