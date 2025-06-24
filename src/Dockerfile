FROM node:20.19.3-slim
WORKDIR /app
COPY package*.json .
RUN npm install
COPY . .
EXPOSE 8080
ENTRYPOINT [ "node", "server.js" ]