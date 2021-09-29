FROM node:14.17.6
WORKDIR /app
COPY ./src/package*.json ./
RUN npm install
COPY . .
EXPOSE 8080
CMD ["node","server.js"]
