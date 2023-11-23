### Dockerfile for Server App ###

FROM node:21.2-alpine

WORKDIR /usr/src/app-backend

COPY package*.json ./

RUN npm install

COPY . .

EXPOSE 3002

CMD ["npm", "start"]
