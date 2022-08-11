FROM node:10-alpine


LABEL author="Mohammed Shaikh"
EXPOSE 3001

RUN mkdir -p /home/node/app/node_modules && chown -R node:node /home/node/app
WORKDIR /home/node/app
COPY . .
USER node
RUN npm install
COPY --chown=node:node . .

VOLUME [ "/home/node/app" ]
CMD [ "node", "index.js" ]
