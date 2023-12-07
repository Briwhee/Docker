FROM node:20.10.0

WORKDIR /app

COPY package*.json /app/

COPY src /app/

RUN npm install

CMD [ "node", "index.js" ]