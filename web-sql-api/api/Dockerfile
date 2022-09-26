FROM node:10-alpine

ENV CONNECTION_STRING=${CONNECTION_STRING}
LABEL author="Mohammed Shaikh"
EXPOSE 3001

WORKDIR /var/www
COPY . .
RUN npm install

VOLUME [ "/var/www" ]
CMD [ "node", "index.js" ]
