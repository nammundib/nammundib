FROM node:4.6
RUN mkdir /app
ADD word-finder /app
WORKDIR /app
RUN npm install
RUN npm install mocha -g
CMD node start.js