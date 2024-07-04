FROM node

WORKDIR /home/node-app

# COPY package.json /home/node-app/
COPY . /home/node-app/

RUN npm install

EXPOSE 80

CMD ["node", "server.js"]
