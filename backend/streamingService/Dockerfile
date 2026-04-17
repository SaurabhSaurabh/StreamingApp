FROM node:18-alpine AS base

WORKDIR /app/streamingService

COPY package*.json ./

RUN npm install 

COPY . .

EXPOSE 3002

CMD ["npm", "run", "start"]
