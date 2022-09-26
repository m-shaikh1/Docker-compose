FROM node:10-alpine

ENV API_URL=${API_URL}
LABEL author="Mohammed Shaikh"
EXPOSE 3000

WORKDIR /var/www
COPY . .
RUN npm install

VOLUME [ "/var/www" ]
CMD [ "node", "index.js" ]
