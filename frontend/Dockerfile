FROM node:16.5.0-alpine

WORKDIR /app

COPY package.json yarn.lock ./

RUN yarn install --silent --frozen-lockfile

COPY . .

EXPOSE 3000

CMD yarn start