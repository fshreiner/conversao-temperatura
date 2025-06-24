FROM node:20.19.3-slim
WORKDIR /app
COPY . .
RUN npm install
EXPOSE 8080
ENTRYPOINT [ "node", "server.js" ]