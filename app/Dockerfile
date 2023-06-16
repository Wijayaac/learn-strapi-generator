FROM strapi/base:latest
FROM node:16.17.0

WORKDIR /usr/src/app

COPY package.json yarn.lock ./
RUN yarn install

COPY . .

EXPOSE 1337

CMD ["yarn", "develop"]
