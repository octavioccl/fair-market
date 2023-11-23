FROM node:21.2-alpine

WORKDIR /usr/src/app-admin

COPY package*.json ./

RUN npm install

COPY . .

EXPOSE 3001

CMD ["npm", "run", "dev"]
