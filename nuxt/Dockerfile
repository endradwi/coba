# Gunakan Node.js sebagai base image
FROM node

WORKDIR /app

COPY . .

RUN npm install
RUN npm run build

ENTRYPOINT  ["node", ".output/server/index.mjs"]