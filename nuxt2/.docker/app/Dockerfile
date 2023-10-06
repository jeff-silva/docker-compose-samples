FROM node:18.16-alpine
WORKDIR /app

COPY . .

EXPOSE $NUXT_PORT

CMD yarn install && yarn dev
