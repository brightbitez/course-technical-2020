#https://hub.docker.com/repository/docker/brightbite/bannavith
FROM node:14.5.0-stretch
WORKDIR /app
COPY package*.json ./
RUN npm install
COPY . .
EXPOSE 4000
CMD [ "npm", "start" ]
