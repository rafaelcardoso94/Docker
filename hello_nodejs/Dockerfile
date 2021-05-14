FROM node:12-alpine

WORKDIR /app

COPY package.json .

RUN npm install

COPY hello.js .

EXPOSE 8080

CMD ["node", "hello.js"]
