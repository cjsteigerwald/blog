FROM node:alpine

WORKDIR /app
# COPY ../.npmrc ./ # for corporate proxy
COPY package.json ./
RUN npm install --loglevel verbose
COPY ./ ./

CMD [ "npm", "start" ]