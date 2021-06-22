FROM node:alpine

RUN mkdir /app
WORKDIR /app

# ENV PATH /app/node_modules/.bin:$PATH

COPY package.json ./

RUN npm install

COPY src src
COPY public public
CMD npm start
