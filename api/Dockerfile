FROM node:10-alpine


LABEL author="Mohammed Shaikh"
EXPOSE 3001

WORKDIR /var/www
COPY . .
RUN npm install

VOLUME [ "/var/www" ]
CMD [ "node", "index.js" ]
