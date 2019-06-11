FROM alpine

LABEL maintainer="rajankit749@gmail.com"

RUN apk add --update nodejs nodejs-npm

COPY . /src

WORKDIR /src

RUN npm install npm@latest -g

EXPOSE 8080

ENTRYPOINT ["node","./app.js"]


