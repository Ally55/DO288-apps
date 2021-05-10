FROM node:latest

RUN mkdir /app-day-7

WORKDIR /app-day-7

COPY server.js /app-day-7

RUN npm install && npm install express && npm install mysql

EXPOSE 3000

CMD ["node", "server.js"]
