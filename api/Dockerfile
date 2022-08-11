from: node:10-alpine

LABEL author="Mohammed Shaikh"
EXPOSE 3001

WORKDIR /usr/node/app
COPY . .
RUN npm install

VOLUME [ "/var/www" ]
CMD [ "npm", "start" ]
