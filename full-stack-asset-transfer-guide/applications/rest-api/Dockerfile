FROM node:14-alpine3.14 AS build
WORKDIR /app
COPY  . /app
RUN npm install
CMD [ "npm","run","prod" ]
