FROM node:21

WORKDIR /app

COPY ./package.json ./package.json

RUN npm install

VOLUME [ "/app" ]

CMD ["npm", "run", "dev"]