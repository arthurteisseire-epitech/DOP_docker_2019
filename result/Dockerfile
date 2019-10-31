FROM node:latest

WORKDIR /usr/src/app

ENV PORT=4242

EXPOSE ${PORT}

COPY . .

RUN npm install

CMD [ "node", "./server.js" ]
