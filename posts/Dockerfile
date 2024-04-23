FROM node:alpine

WORKDIR /app
COPY ../.npmrc ./
COPY package.json ./
RUN npm install --loglevel verbose
COPY ./ ./

CMD [ "npm", "start" ]