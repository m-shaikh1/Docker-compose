FROM node:10-alpine

LABEL author="Mohammed Shaikh"
EXPOSE 80

WORKDIR /usr/src/app
COPY . .
RUN npm install

VOLUME [ "/var/www" ]
CMD [ "node", "server.js" ]
