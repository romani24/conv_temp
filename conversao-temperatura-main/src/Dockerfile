FROM node
WORKDIR /app
COPY package*.json ./
run npm install
COPY . .
EXPOSE 8080
CMD ["node, "server.js"]