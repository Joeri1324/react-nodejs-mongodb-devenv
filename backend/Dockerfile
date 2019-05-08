FROM node:10.15.3

ADD . /backend

WORKDIR /backend

RUN rm -rf node_modules/

RUN npm install

RUN npm build

CMD ["npm", "start"]
