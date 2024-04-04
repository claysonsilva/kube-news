FROM node
WORKDIR /app
COPY package*.json .
RUN npm install
COPY . .
EXPOSE 8080
ENTRYPOINT [ "Node", "server.js" ]