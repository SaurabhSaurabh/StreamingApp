FROM node:18-alpine AS base

WORKDIR /app/chatService

COPY package*.json ./
RUN npm install 

COPY . .

EXPOSE 3004

CMD ["npm", "run", "start"]
