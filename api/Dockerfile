FROM node:19-alpine3.17

EXPOSE 3000

ENV PORT 3000

WORKDIR /api

COPY package*.json .

RUN npm install

COPY . .

CMD ["npm", "run", "dev"]

