FROM node:21-alpine

WORKDIR /app

RUN npm i -g @nestjs/cli

COPY ./package.json ./package.json

RUN npm install

VOLUME [ "/app" ]

CMD ["npm", "run", "start:dev"]