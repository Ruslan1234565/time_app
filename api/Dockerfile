# Dockerfile для backend/api (Node.js)
FROM node:20-alpine
WORKDIR /app
COPY package*.json ./
RUN npm ci
COPY . .
EXPOSE 8080
CMD ["node", "index.mjs"] 