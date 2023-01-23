FROM node:18.11.0
WORKDIR /app
COPY package*.json ./
run npm install
COPY . .
EXPOSE 8080
CMD ["node, "server.js"]