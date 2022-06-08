# front

FROM node:lts-alpine

COPY ./ /app/

RUN apk update

WORKDIR /app

RUN npm install

CMD ["npm", "start"]
