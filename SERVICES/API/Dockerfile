FROM node:16-alpine

WORKDIR /srv

COPY package*.json ./

RUN npm install

COPY . .

ENV PORT=4000

EXPOSE 4000

CMD ["npm", "start"]