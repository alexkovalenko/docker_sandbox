FROM node:alpine

WORKDIR '/usr/webapp'

COPY package.json .

RUN npm install

COPY . .

CMD ["npm","start"]
