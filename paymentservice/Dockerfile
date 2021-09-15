FROM node:14-slim

WORKDIR /app

COPY . .

RUN npm install 

EXPOSE 50051

CMD ["node", "client.js", "index.js", "server.js"]