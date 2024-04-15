FROM node:14
EXPOSE 8080
WORKDIR /opt/server
COPY package.json .
COPY server.js .
RUN npm install
ENV MONGO=true
CMD [ "node", "server.js" ]

# note : here catalogue.js automatically load by node:14