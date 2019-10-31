FROM node:latest

WORKDIR /usr/src/app

EXPOSE 80:4242

COPY . .

RUN npm install

CMD [ "node", "./server.js" ]
