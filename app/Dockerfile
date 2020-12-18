FROM node:14-alpine

WORKDIR /src

RUN npm i -g node-dev

ADD package.json /src 

RUN npm i

ADD . /src 

RUN npm run build 

CMD npm start