FROM node:14-slim

WORKDIR /app

COPY . .

RUN npm install 

EXPOSE ?

CMD ["node", "client.js", "index.js", "server.js"]