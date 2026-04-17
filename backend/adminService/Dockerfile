FROM node:18-alpine AS base

WORKDIR /app/adminService

COPY package*.json ./
RUN npm install 

COPY . .

EXPOSE 3003

CMD ["npm", "run", "start"]
