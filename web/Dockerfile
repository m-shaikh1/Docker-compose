FROM node:10-alpine

LABEL author="Mohammed Shaikh"
EXPOSE 80

WORKDIR /usr/src/app
COPY . .
RUN npm install

VOLUME [ "/usr/src/app" ]
CMD [ "node", "server.js" ]
