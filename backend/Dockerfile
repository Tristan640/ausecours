FROM node:20-alpine

ADD . /app
WORKDIR /app

RUN npm i --omit=dev

EXPOSE 23000

USER node
CMD npm run initbdd; npm run start