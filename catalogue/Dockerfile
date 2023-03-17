FROM node:14

EXPOSE 8080

WORKDIR /opt/server

COPY package.json /opt/server/

#npn install will get the dependencies of the node js project
RUN npm install

COPY server.js /opt/server/

ENTRYPOINT ["node", "server.js"]

