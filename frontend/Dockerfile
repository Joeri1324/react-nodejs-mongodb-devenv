FROM node:10.15.3

ADD . /frontend

WORKDIR /frontend

RUN rm -rf node_modules/

RUN npm install

RUN npm build

CMD ["npm", "start"]
