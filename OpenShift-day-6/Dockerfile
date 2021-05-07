FROM node:latest

RUN mkdir /app-day-6

WORKDIR /app-day-6

COPY Server.js /app-day-6

RUN npm install

RUN npm install express

EXPOSE 3000

CMD ["node", "Server.js"]
