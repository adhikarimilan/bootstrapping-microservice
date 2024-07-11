FROM node:19-alpine

WORKDIR /usr/src/app

COPY package.json ./

RUN npm install --only=production

COPY index.js ./

COPY .env ./



CMD ["node", "index.js"]