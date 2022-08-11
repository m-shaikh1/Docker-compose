from: node:10-alpine

LABEL author="Mohammed Shaikh"

COPY . /var/www
WORKDIR /var/www
RUN npm install

VOLUME [ "/var/www" ]
CMD [ "npm", "start" ]
