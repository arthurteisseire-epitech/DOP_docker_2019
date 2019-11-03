FROM node:latest

WORKDIR /usr/src/app

ENV PORT=80

EXPOSE 80

COPY . .

RUN npm install

CMD [ "node", "./server.js" ]
